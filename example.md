here's new chart



    <!-- This is the container for your embedded chart -->
    <div class="bg-white p-6 rounded-2xl shadow-lg w-full max-w-3xl">
        <h2 class="text-2xl font-semibold mb-4 text-center">Bar Chart</h2>
        <p class="text-gray-600 text-center mb-4">Ideal for comparing values across different categories.</p>
        
        <!-- 2. Create a <canvas> element where the chart will be drawn. -->
        <div class="relative h-80">
            <canvas id="embeddedBarChart"></canvas>
        </div>
    </div>

    <!-- 3. Add the JavaScript to create and configure the chart -->
    <script>
        // Use an IIFE (Immediately Invoked Function Expression) to avoid polluting the global scope
        (() => {
            // Get the context of the canvas element we want to draw on
            const barCtx = document.getElementById('embeddedBarChart').getContext('2d');
            
            // Create a new chart instance
            const barChart = new Chart(barCtx, {
                type: 'bar',
                data: {
                    labels: ['January', 'February', 'March', 'April', 'May', 'June'],
                    datasets: [{
                        label: 'Monthly Sales',
                        data: [65, 59, 80, 81, 56, 55],
                        backgroundColor: [
                            'rgba(255, 99, 132, 0.2)',
                            'rgba(54, 162, 235, 0.2)',
                            'rgba(255, 206, 86, 0.2)',
                            'rgba(75, 192, 192, 0.2)',
                            'rgba(153, 102, 255, 0.2)',
                            'rgba(255, 159, 64, 0.2)'
                        ],
                        borderColor: [
                            'rgba(255, 99, 132, 1)',
                            'rgba(54, 162, 235, 1)',
                            'rgba(255, 206, 86, 1)',
                            'rgba(75, 192, 192, 1)',
                            'rgba(153, 102, 255, 1)',
                            'rgba(255, 159, 64, 1)'
                        ],
                        borderWidth: 1,
                        borderRadius: 8,
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        y: {
                            beginAtZero: true
                        }
                    },
                    plugins: {
                        legend: {
                            display: false // Hide legend for single dataset
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    return `Sales: ${context.parsed.y}`;
                                }
                            }
                        }
                    }
                }
            });
        })();
    </script>

</body>
</html>

   <div class="bg-white p-6 rounded-2xl shadow-lg w-full max-w-3xl">
        <h2 class="text-2xl font-semibold mb-4 text-center">Bar Chart</h2>
        <p class="text-gray-600 text-center mb-4">Ideal for comparing values across different categories.</p>
        
        <!-- 2. Create a <canvas> element where the chart will be drawn. -->
        <div class="relative h-80">
            <canvas id="embeddedBarChart"></canvas>
        </div>
    </div>
…                                label: function(context) {
                                    return `Sales: ${context.parsed.y}`;
                                }
                            }
                        }
                    }
                }
            });
        })();
    </script>
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
