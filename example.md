<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Bar Chart</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://d3js.org/d3.v7.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            color: #1f2937;
        }
        .chart-container {
            background-color: white;
            padding: 2rem;
            border-radius: 0.75rem;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            width: 90%;
            max-width: 800px;
        }
        .bar {
            fill: #4f46e5;
            transition: fill 0.2s ease-in-out;
        }
        .bar:hover {
            fill: #6366f1;
        }
        .tooltip {
            position: absolute;
            background-color: rgba(31, 41, 55, 0.9);
            color: white;
            padding: 0.5rem 0.75rem;
            border-radius: 0.375rem;
            font-size: 0.875rem;
            pointer-events: none;
            opacity: 0;
            transition: opacity 0.2s ease-in-out;
            transform: translate(-50%, -100%);
        }
        .axis-label {
            font-size: 0.875rem;
            font-weight: 500;
            fill: #4b5563;
        }
         .grid line {
            stroke: #e5e7eb;
            stroke-opacity: 0.7;
            shape-rendering: crispEdges;
        }
        .grid path {
            stroke-width: 0;
        }
    </style>
</head>
<body class="bg-gray-100">

    <div class="chart-container">
        <h1 class="text-2xl font-bold mb-2 text-center text-gray-800">Monthly Revenue</h1>
        <p class="text-center text-gray-500 mb-6">Fictional data for demonstration</p>
        <div id="chart-area"></div>
    </div>

    <script>
        // --- 1. Data ---
        const data = [
            { month: 'Jan', revenue: 15234 },
            { month: 'Feb', revenue: 18987 },
            { month: 'Mar', revenue: 23456 },
            { month: 'Apr', revenue: 20123 },
            { month: 'May', revenue: 28765 },
            { month: 'Jun', revenue: 32456 },
            { month: 'Jul', revenue: 30123 },
            { month: 'Aug', revenue: 35678 },
            { month: 'Sep', revenue: 33456 },
            { month: 'Oct', revenue: 38901 },
            { month: 'Nov', revenue: 41234 },
            { month: 'Dec', revenue: 45678 },
        ];

        // --- 2. Setup ---
        const chartArea = d3.select("#chart-area");

        // Tooltip
        const tooltip = d3.select("body").append("div")
            .attr("class", "tooltip");

        function drawChart() {
            // Clear previous chart
            chartArea.selectAll("*").remove();
            
            const containerWidth = parseInt(chartArea.style("width"));

            const margin = { top: 20, right: 20, bottom: 70, left: 60 };
            const width = containerWidth - margin.left - margin.right;
            const height = 400 - margin.top - margin.bottom;

            const svg = chartArea.append("svg")
                .attr("width", width + margin.left + margin.right)
                .attr("height", height + margin.top + margin.bottom)
                .append("g")
                .attr("transform", `translate(${margin.left}, ${margin.top})`);

            // --- 3. Scales ---
            const xScale = d3.scaleBand()
                .domain(data.map(d => d.month))
                .range([0, width])
                .padding(0.2);

            const yScale = d3.scaleLinear()
                .domain([0, d3.max(data, d => d.revenue) * 1.1]) // Add 10% padding to top
                .range([height, 0]);

            // --- 4. Axes ---
            const xAxis = d3.axisBottom(xScale);
            const yAxis = d3.axisLeft(yScale)
                .ticks(5)
                .tickFormat(d => `$${d3.format(".2s")(d).replace(/G/, "B").replace(/M/, "M").replace(/k/, "K")}`);

            svg.append("g")
                .attr("transform", `translate(0, ${height})`)
                .call(xAxis)
                .selectAll("text")
                .style("text-anchor", "end")
                .attr("dx", "-.8em")
                .attr("dy", ".15em")
                .attr("transform", "rotate(-45)");
            
            svg.append("g")
                .call(yAxis);

            // Add Y-axis grid lines
            svg.append("g")			
                .attr("class", "grid")
                .call(d3.axisLeft(yScale)
                    .ticks(5)
                    .tickSize(-width)
                    .tickFormat("")
                );

            // --- 5. Draw Bars ---
            svg.selectAll(".bar")
                .data(data)
                .enter()
                .append("rect")
                .attr("class", "bar")
                .attr("x", d => xScale(d.month))
                .attr("y", d => yScale(0)) // Start at the bottom for animation
                .attr("width", xScale.bandwidth())
                .attr("height", 0) // Start with 0 height for animation
                .on("mouseover", (event, d) => {
                    tooltip.style("opacity", 1);
                })
                .on("mousemove", (event, d) => {
                    const formattedRevenue = d3.format("$,.0f")(d.revenue);
                    tooltip.html(`<strong>${d.month}</strong><br>Revenue: ${formattedRevenue}`)
                        .style("left", `${event.pageX}px`)
                        .style("top", `${event.pageY - 10}px`);
                })
                .on("mouseout", () => {
                    tooltip.style("opacity", 0);
                })
                .transition()
                .duration(800)
                .attr("y", d => yScale(d.revenue))
                .attr("height", d => height - yScale(d.revenue))
                .delay((d, i) => i * 50);

            // --- 6. Labels ---
            // X-axis label
            svg.append("text")
                .attr("class", "axis-label")
                .attr("text-anchor", "middle")
                .attr("x", width / 2)
                .attr("y", height + margin.bottom - 10)
                .text("Month");

            // Y-axis label
            svg.append("text")
                .attr("class", "axis-label")
                .attr("text-anchor", "middle")
                .attr("transform", "rotate(-90)")
                .attr("y", -margin.left + 20)
                .attr("x", -height / 2)
                .text("Revenue (USD)");
        }
        
        // Initial draw
        drawChart();

        // Redraw chart on window resize
        window.addEventListener('resize', drawChart);

    </script>

</body>
</html>
