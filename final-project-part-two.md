<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Final Project II | Amirkhon Khamidov's Portfolio</title>
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
                    <li><a href="final-project-part-one" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project I</a></li>
                    <li><a href="final-project-part-two" class="text-blue-600 font-bold transition-colors">Final Project II</a></li>
                    <li><a href="final-project-part-three" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project III</a></li>
                </ul>
            </nav>
        </header>

        <hr class="border-slate-200 mb-10">

        <!-- Main Content Area -->
        <main class="bg-white p-6 sm:p-8 rounded-xl shadow-md border border-slate-200 content-body">
            <h1 class="text-4xl font-bold text-slate-900 mb-6 text-center">Final Project: Wireframes & User Research</h1>
            
            <!-- Story Outline -->
            <section>
                <h2>Story Outline and Flow</h2>
                <p class="text-slate-600 leading-relaxed mb-4">My story centers on the sharp rise in <strong>Uzbekistan’s housing prices (2022–2024)</strong>. I want to explore whether the influx of <strong>Russian migrants acted as a catalyst</strong>, while also situating this trend in the <strong>regional context</strong> (Kazakhstan, Kyrgyzstan) and considering <strong>other demand/supply factors</strong>.</p>
                <h3 class="!mt-6">Setup, Conflict, and Resolution</h3>
                <ul class="list-disc list-inside space-y-3 text-slate-600 leading-relaxed">
                    <li><strong>Setup (Part I):</strong> Uzbekistan’s housing prices surged sharply between 2022–2024. The initial hypothesis was that the influx of Russian migrants could help explain this change, focusing the narrative narrowly on Uzbekistan.</li>
                    <li><strong>Conflict (Part II):</strong> A narrow focus raises questions: “What about neighboring countries like Kazakhstan?” This risks an oversimplified narrative. The tension lies in expanding the story to include regional context and other economic drivers without overwhelming the reader.</li>
                    <li><strong>Resolution (Part II):</strong> I expanded the storyline by adding a <strong>regional layer</strong> (Kazakhstan, Kyrgyzstan) and a <strong>“drivers wall”</strong> of other economic factors (wages, population, etc.). This allows me to test if these alternative explanations broke from historical trends, making the migration catalyst theory more plausible.</li>
                </ul>
                <div class="mt-6 text-center">
                    <a href="https://preview.shorthand.com/fmoJFGXger9iCo5F/responsive/desktop" target="_blank" rel="noopener noreferrer" class="inline-block bg-blue-600 text-white font-semibold py-2 px-5 rounded-lg hover:bg-blue-700 transition-colors">
                        📍 View Storyboard Preview in Shorthand
                    </a>
                </div>
            </section>
            
            <hr class="border-slate-200 my-8">

            <!-- Design -->
            <section>
                <h2>Design: Data Visuals & Iterations</h2>
                 <p class="text-slate-600 leading-relaxed mb-4">The visuals evolved from a single-country focus to a broader regional and multi-factor analysis.</p>
                <div class="space-y-6">
                    <div>
                        <h3 class="text-xl !mt-4 font-bold text-slate-800">Visual 1 — Regional Housing Price Index (2018–2025)</h3>
                        <p class="text-slate-600"><strong>Type:</strong> Indexed line chart. <strong>Why:</strong> Enables cross-country comparison regardless of different price levels. <strong>Iteration:</strong> Evolved from an Uzbekistan-only chart to a three-country comparison with event annotations and improved labeling.</p>
                    </div>
                     <div>
                        <h3 class="text-xl !mt-4 font-bold text-slate-800">Visual 2 — Russian Migrant Arrivals (2019–2024)</h3>
                        <p class="text-slate-600"><strong>Type:</strong> Small multiples line charts. <strong>Why:</strong> Clearer to see the timing and relative magnitude of spikes. <strong>Iteration:</strong> Grew from a single chart to three small multiples for direct comparison.</p>
                    </div>
                     <div>
                        <h3 class="text-xl !mt-4 font-bold text-slate-800">Visual 3 — “Drivers Wall” (Supply & Demand Factors)</h3>
                        <p class="text-slate-600"><strong>Type:</strong> Four small-multiples line charts. <strong>Why:</strong> Allows for a quick scan of other potential drivers like income, population, and construction costs. <strong>Iteration:</strong> Standardized scales and added "breakout vs. trend" tags for clarity.</p>
                    </div>
                </div>
            </section>

            <hr class="border-slate-200 my-8">

            <!-- User Research -->
            <section>
                 <h2>User Research</h2>
                 <p class="mb-6 text-slate-600 leading-relaxed">I conducted five semi-structured interviews to test comprehension, interpretation, and credibility, targeting policy students and general readers.</p>
                 <h3 class="!mt-6">Key Insights & Quotes</h3>
                 <ul class="list-disc list-inside space-y-3 text-slate-600 leading-relaxed">
                     <li><strong>Regional context is crucial (4/5):</strong> “If Kazakhstan sits between Russia and Uzbekistan, I immediately wonder what happened in Kazakhstan. You can’t skip that part.”</li>
                     <li><strong>Migration data needs a longer history (3/5):</strong> “Show me the trend before 2022, otherwise I don’t know if this spike is unusual.”</li>
                     <li><strong>Be cautious with causality (3/5):</strong> “This looks like correlation. Please keep reminding me you’re not saying one causes the other.”</li>
                     <li><strong>The "Drivers Wall" was mixed (3/5):</strong> Some found it useful, others found it too dense. The consensus was to show the top 4 drivers.</li>
                 </ul>
            </section>
            
            <hr class="border-slate-200 my-8">

            <!-- Changes for Part III -->
            <section>
                 <h2>Identified Changes for Part III</h2>
                 <p class="mb-6 text-slate-600 leading-relaxed">Based on user feedback, the following changes are planned for the final version.</p>
                 <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse">
                        <thead class="bg-slate-100">
                            <tr>
                                <th class="p-3 font-semibold text-sm text-slate-700 border-b">Research Synthesis</th>
                                <th class="p-3 font-semibold text-sm text-slate-700 border-b">Anticipated Changes</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-slate-200">
                            <tr>
                                <td class="p-3 text-slate-600">Regional context is important</td>
                                <td class="p-3 text-slate-600">Keep Uzbekistan/Kazakhstan/Kyrgyzstan comparison upfront.</td>
                            </tr>
                            <tr>
                                <td class="p-3 text-slate-600">Longer migration series needed</td>
                                <td class="p-3 text-slate-600">Extend migration flows to 2019–2024 to show a baseline.</td>
                            </tr>
                            <tr>
                                <td class="p-3 text-slate-600">Clarify correlation vs. causation</td>
                                <td class="p-3 text-slate-600">Add a persistent “Association, not causation” badge and a limitations section.</td>
                            </tr>
                             <tr>
                                <td class="p-3 text-slate-600">Balance the "Drivers Wall"</td>
                                <td class="p-3 text-slate-600">Prune to 4 key drivers in the main story, with others in an appendix.</td>
                            </tr>
                             <tr>
                                <td class="p-3 text-slate-600">Improve mobile readability</td>
                                <td class="p-3 text-slate-600">Increase font sizes and simplify legends for small screens.</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </section>
            
            <hr class="border-slate-200 my-8">
            
            <!-- Reflection -->
            <section>
                <h2>Reflection</h2>
                <p class="text-slate-600 leading-relaxed">My scope grew intentionally from an Uzbekistan-only story to a regional narrative. User research was critical in recentering the story, emphasizing the need for regional context, a longer data baseline, and explicit clarification of the story's limitations (correlation, not causation). For Part III, the focus will be on refining the visuals based on this feedback to create a clear and credible visual story.</p>
            </section>

        </main>
        
        <!-- Footer -->
        <footer class="text-center text-sm text-slate-500 mt-12">
             <h3 class="font-semibold text-slate-600 mb-2">AI Acknowledgement</h3>
             <p>AI was used to fix my sentences and streamline my thoughts.</p>
            <p class="mt-4">© 2024 Amirkhon Khamidov</p>
        </footer>

    </div>
</body>
</html>

