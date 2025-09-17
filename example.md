<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Embedding a Chart</title>
    <!-- 1. Include the Chart.js library from a CDN -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <!-- Optional: Tailwind CSS for basic styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-200 flex items-center justify-center min-h-screen p-4">

    <div class="bg-white p-6 sm:p-8 rounded-xl shadow-lg w-full max-w-3xl">
        <h1 class="text-xl sm:text-2xl font-bold mb-4 text-center text-gray-800">Example of an Embedded Bar Chart</h1>
        
        <!-- 2. Add a <canvas> element where the chart will be drawn. -->
        <!-- The parent div helps control the size of the chart. -->
        <div class="relative h-96">
            <canvas id="myEmbeddedChart"></canvas>
        </div>
    </div>

    <script>
        // 3. Write the JavaScript code to create and configure the chart.
        
        // Find the canvas element you created above
        const ctx = document.getElementById('myEmbeddedChart').getContext('2d');

        // Create the chart instance
        const myBarChart = new Chart(ctx, {
            type: 'bar', // Specify the chart type
            data: {
                // Labels for the X-axis
                labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
                // Datasets to display
                datasets: [{
                    label: '# of Votes',
                    data: [12, 19, 3, 5, 2, 3], // The actual data points
                    backgroundColor: [ // Bar fill colors
                        'rgba(255, 99, 132, 0.2)',
                        'rgba(54, 162, 235, 0.2)',
                        'rgba(255, 206, 86, 0.2)',
                        'rgba(75, 192, 192, 0.2)',
                        'rgba(153, 102, 255, 0.2)',
                        'rgba(255, 159, 64, 0.2)'
                    ],
                    borderColor: [ // Bar border colors
                        'rgba(255, 99, 132, 1)',
                        'rgba(54, 162, 235, 1)',
                        'rgba(255, 206, 86, 1)',
                        'rgba(75, 192, 192, 1)',
                        'rgba(153, 102, 255, 1)',
                        'rgba(255, 159, 64, 1)'
                    ],
                    borderWidth: 1,
                    borderRadius: 5
                }]
            },
            options: {
                // Make the chart responsive to its container size
                responsive: true,
                maintainAspectRatio: false,
                scales: {
                    y: {
                        beginAtZero: true // Start the Y-axis at 0
                    }
                },
                plugins: {
                    legend: {
                        display: true, // Show the legend
                        position: 'top',
                    }
                }
            }
        });
    </script>

</body>
</html>
