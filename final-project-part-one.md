<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Final Project I | Amirkhon Khamidov's Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .content-body h2 {
            font-size: 1.875rem; /* 3xl */
            font-weight: 700;
            color: #1e293b; /* slate-900 */
            margin-bottom: 1.5rem; /* mb-6 */
            margin-top: 2.5rem; /* mt-10 */
        }
        .content-body h3 {
            font-size: 1.5rem; /* 2xl */
            font-weight: 700;
            color: #1e293b; /* slate-900 */
            margin-bottom: 1rem; /* mb-4 */
            margin-top: 2rem; /* mt-8 */
        }
        .content-body blockquote {
            border-left: 4px solid #cbd5e1; /* slate-300 */
            padding-left: 1rem;
            margin: 1.5rem 0;
            color: #475569; /* slate-600 */
            font-style: italic;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- Main Container -->
    <div class="container mx-auto max-w-4xl p-4 sm:p-6 md:p-8">

        <!-- Header and Navigation -->
        <header class="text-center mb-10">
            <h1 class="text-4xl font-bold text-slate-900 mb-2">Amirkhon Khamidov</h1>
            <p class="text-xl text-slate-600">Data & Policy Portfolio</p>
            <nav class="mt-6">
                <ul class="flex flex-wrap justify-center space-x-4 sm:space-x-6">
                    <li><a href="index.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Home</a></li>
                    <li><a href="dataviz-examples.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Data Viz Examples</a></li>
                    <li><a href="critique-by-design.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Critique by Design</a></li>
                    <li><a href="final-project-part-one" class="text-blue-600 font-bold transition-colors">Final Project I</a></li>
                    <li><a href="final-project-part-two" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project II</a></li>
                    <li><a href="final-project-part-three" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project III</a></li>
                </ul>
            </nav>
        </header>

        <hr class="border-slate-200 mb-10">

        <!-- Main Content Area -->
        <main class="bg-white p-6 sm:p-8 rounded-xl shadow-md border border-slate-200 content-body">
            <h1 class="text-4xl font-bold text-slate-900 mb-6 text-center">Final Project: Proposal & Outline</h1>
            <blockquote>Important note: this includes major elements of Part I.</blockquote>
            <p class="text-slate-600 text-lg leading-relaxed">
                In recent years, Uzbekistan has experienced a dramatic rise in housing prices, particularly in the capital city, Tashkent. This project will tell the story of how factors like migration, supply constraints, and local demand shifts have interacted to shape the current housing market.
            </p>
            
            <h3 class="!mt-6">Story Structure</h3>
            <ul class="list-disc list-inside space-y-2 text-slate-600 leading-relaxed">
                <li><strong>Setup:</strong> Uzbekistan’s housing market was relatively stable for nearly a decade, with moderate changes in price.</li>
                <li><strong>Conflict:</strong> Starting around 2022, prices spiked dramatically. Competing explanations emerged, including migration shocks from Russia, limited housing construction, and growing local demand.</li>
                <li><strong>Resolution:</strong> By visualizing and comparing these factors, the project will highlight how migration shocks amplified existing supply and demand pressures, helping us better understand the dynamics of Tashkent’s housing crisis.</li>
            </ul>

            <hr class="border-slate-200 my-8">

            <!-- Sketches -->
            <section>
                <h2>Initial Sketches</h2>
                <p class="mb-6 text-slate-600 leading-relaxed">I plan to use sketches to map out the story and the visuals.</p>
                
                <h3 class="text-xl !mt-4">1. Line Chart of Housing Price Growth</h3>
                <p class="mb-4 text-slate-600 leading-relaxed">This chart aims to clearly show the sudden upward inflection in prices, with vertical markers for the two waves of Russian mobilization.</p>
                <div class="w-full my-4 border border-slate-200 rounded-lg overflow-hidden shadow-md">
                    <iframe title="Recent housing price spikes in the last 3 years" aria-label="Line chart" id="datawrapper-chart-cLL6z" src="https://datawrapper.dwcdn.net/cLL6z/1/" scrolling="no" frameborder="0" style="width: 100%; border: none;" height="762"></iframe>
                </div>
                 <figure class="text-center my-6">
                    <img src="https://raw.githubusercontent.com/akhamidogit/dataviz/main/Housing%20price%20changes.png" alt="Housing price changes sketch" class="max-w-full sm:max-w-[70%] mx-auto border border-slate-200 rounded-lg p-1 bg-slate-50 shadow-sm">
                </figure>


                <h3 class="text-xl !mt-8">2. Conceptual Diagram of Supply and Demand</h3>
                 <p class="mb-4 text-slate-600 leading-relaxed">This sketch will serve as a framework for explaining the competing factors and their relative contributions.</p>
                 <figure class="text-center my-6">
                    <img src="https://raw.githubusercontent.com/akhamidogit/dataviz/main/Conceptual%20House%20prices.png" alt="Conceptual housing price factors sketch" class="max-w-full sm:max-w-[70%] mx-auto border border-slate-200 rounded-lg p-1 bg-slate-50 shadow-sm">
                </figure>

                <blockquote>
                    <h4 class="font-bold text-slate-700 not-italic">Context on Supply and Demand Factors</h4>
                    <p class="mt-2"><strong>Demand Factors:</strong> Interest rates, population growth, migration patterns, and rising incomes all boost housing demand. Low rates make borrowing easier, while more people competing for limited housing stock drives up prices, especially in urban areas.</p>
                    <p class="mt-2"><strong>Supply Factors:</strong> The cost of building materials, land availability, and strict land-use regulations constrain housing supply. When it's more expensive or difficult to build, fewer homes are available, leading to higher prices.</p>
                </blockquote>
            </section>

             <hr class="border-slate-200 my-8">

            <!-- Data -->
            <section>
                <h2>The Data</h2>
                <p class="mb-6 text-slate-600 leading-relaxed">The project relies on a combination of scraped housing data, official migration statistics, and supplementary macroeconomic indicators.</p>
                <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse">
                        <thead class="bg-slate-100">
                            <tr>
                                <th class="p-3 font-semibold text-sm text-slate-700 border-b">Name</th>
                                <th class="p-3 font-semibold text-sm text-slate-700 border-b">URL</th>
                                <th class="p-3 font-semibold text-sm text-slate-700 border-b">Description</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-slate-200">
                            <tr>
                                <td class="p-3 text-slate-600">Housing price dataset</td>
                                <td class="p-3"><a href="https://github.com/akhamidogit/dataviz/blob/main/2022_2024_housing_prices.xlsx" class="text-blue-600 hover:underline">2022–2024</a>, <a href="https://github.com/akhamidogit/dataviz/blob/main/2025_08_housing_price.xlsx" class="text-blue-600 hover:underline">2025</a></td>
                                <td class="p-3 text-slate-600">Monthly scraped OLX listings, cleaned and aggregated into median prices.</td>
                            </tr>
                            <tr>
                                <td class="p-3 text-slate-600">Migration statistics</td>
                                <td class="p-3 text-slate-500 italic">(To be added)</td>
                                <td class="p-3 text-slate-600">Official data from stat.uz on inflows of foreign nationals (focus on Russians).</td>
                            </tr>
                            <tr>
                                <td class="p-3 text-slate-600">Supplementary data</td>
                                <td class="p-3"><a href="https://stat.uz" class="text-blue-600 hover:underline">stat.uz</a></td>
                                <td class="p-3 text-slate-600">Macroeconomic indicators: housing stock, population growth, household incomes.</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </section>
            
             <hr class="border-slate-200 my-8">

            <!-- Method -->
            <section>
                <h2>Method and Medium</h2>
                <p class="mb-4 text-slate-600 leading-relaxed">For my final product, I plan to use a combination of tools to weave a clear and engaging story:</p>
                <ul class="list-disc list-inside space-y-2 text-slate-600 leading-relaxed">
                    <li><strong>Tableau</strong> for interactive charts (line charts, bar charts, factor breakdowns).</li>
                    <li><strong>Datawrapper</strong> for clean, static visuals when simplicity is best.</li>
                    <li><strong>Shorthand</strong> to bring everything together into a narrative story with scrolling text, images, and embedded charts.</li>
                </ul>
            </section>

        </main>

        <!-- Footer -->
        <footer class="text-center text-sm text-slate-500 mt-12">
             <h3 class="font-semibold text-slate-600 mb-2">AI Acknowledgement</h3>
             <p>I used AI (ChatGPT) to help fix grammar the initial structure and wording of my Part I proposal, including organizing sections, polishing language, and aligning the content with the GitHub template. The ideas, topic selection, and data sources are my own.</p>
            <p class="mt-4">© 2025 Amirkhon Khamidov</p>
        </footer>

    </div>
</body>
</html>

