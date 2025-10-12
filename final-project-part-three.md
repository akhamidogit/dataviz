
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Final Project III | Amirkhon Khamidov's Portfolio</title>
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
                    <li><a href="final-project-part-one.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project I</a></li>
                    <li><a href="final-project-part-two.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project II</a></li>
                    <li><a href="final-project-part-three.html" class="text-blue-600 font-bold transition-colors">Final Project III</a></li>
                </ul>
            </nav>
        </header>

        <hr class="border-slate-200 mb-10">

        <!-- Main Content Area -->
        <main class="bg-white p-6 sm:p-8 rounded-xl shadow-md border border-slate-200 content-body">
            <h1 class="text-4xl font-bold text-slate-900 mb-6 text-center">Final Project: The Story & Reflections</h1>
            
            <!-- Final Story -->
            <section>
                <h2>The Final Data Story</h2>
                <p class="text-slate-600 leading-relaxed mb-4">
                    The final story, "The Central Asian Housing Puzzle," examines the unprecedented surge in Uzbekistan's housing prices from 2022 to 2024. The narrative investigates the potent link between the influx of Russian migrants and the price spike, situating the trend within a broader regional context and carefully weighing other economic drivers to provide a balanced, evidence-based account.
                </p>
                <div class="mt-6 text-center">
                    <a href="https://preview.shorthand.com/fmoJFGXger9iCo5F/responsive/desktop" target="_blank" rel="noopener noreferrer" class="inline-block bg-blue-600 text-white font-semibold py-3 px-6 rounded-lg hover:bg-blue-700 transition-colors text-lg">
                        <strong>View the Final Story on Shorthand</strong>
                    </a>
                </div>
            </section>
            
            <hr class="border-slate-200 my-8">

            <!-- Changes -->
            <section>
                <h2>Changes Made Since Part II</h2>
                <p class="text-slate-600 leading-relaxed">
                    The user feedback from Part II was the blueprint for the final iteration of this project. The changes were not just cosmetic; they fundamentally improved the clarity and credibility of the narrative.
                </p>
                <ul class="list-disc list-inside space-y-3 mt-4 text-slate-600 leading-relaxed">
                    <li><strong>Simplified the Core Visual:</strong> Early feedback suggested that my initial price charts were too complex. In response, I replaced them with a simple, powerful bar chart showing the average annual growth in housing prices. This single visual makes the extraordinary nature of 2022 and 2023 immediately apparent, serving as a much stronger narrative hook.</li>
                    <li><strong>Strengthened the Regional Context:</strong> I fully committed to the regional analysis by ensuring the comparison with Kazakhstan and Kyrgyzstan was a central thread, not an afterthought. This addresses the feedback that an Uzbekistan-only story felt incomplete.</li>
                    <li><strong>Emphasized Analytical Honesty:</strong> To address valid concerns about implying causation, I added a clear and prominent "Methods and Limitations" section to the final story. This explicitly states that the analysis demonstrates a strong association, not a direct causal link, which respects the audience's analytical rigor.</li>
                    <li><strong>Streamlined the "Drivers Wall":</strong> The feedback on the "drivers wall" was mixed, with some finding it dense. I pruned it to the four most critical economic factors. This retained the analytical depth of considering alternative explanations while making the story more focused and digestible.</li>
                </ul>
            </section>

            <hr class="border-slate-200 my-8">

            <!-- Audience -->
            <section>
                 <h2>The Audience</h2>
                 <p class="text-slate-600 leading-relaxed">
                    My primary audience is policy-minded graduate students and early-career analysts. This group is trained to look for nuance and question simple explanations. The user interviews in Part II confirmed they would immediately seek context and consider alternative factors.
                 </p>
                 <p class="mt-4 text-slate-600 leading-relaxed">
                    This understanding directly shaped the final product. For instance, the decision to include the "drivers wall" was to proactively address their skepticism. It demonstrates that other key economic variables were considered and found to be following their historical trends, making the migration shock a more plausible catalyst. Similarly, the inclusion of an explicit limitations section was crucial for building credibility with an audience that values analytical transparency.
                 </p>
            </section>
            
            <hr class="border-slate-200 my-8">

            <!-- Design Decisions -->
            <section>
                 <h2>Final Design Decisions</h2>
                 <p class="text-slate-600 leading-relaxed">
                    The most impactful design decision was shifting to a **bar chart for year-over-year price growth**. This choice was a direct result of user feedback asking for a clearer, more immediate way to see the price spike. A bar chart excels at comparing discrete values, and it instantly communicates the magnitude of the 2022-2023 increase relative to previous years. It's simple, direct, and serves the story's hook perfectly.
                 </p>
                 <p class="mt-4 text-slate-600 leading-relaxed">
                    For the migration data, **small multiples** remained the best choice. Placing three synchronized charts side-by-side allows for effortless comparison of the timing and scale of the migration spike across the three countries. This visual structure does the comparative work for the reader, reinforcing the idea of a shared regional event. Finally, the overall aesthetic was kept clean and minimalist, using a colorblind-safe palette and direct labeling to ensure the data and the narrative remained the central focus.
                 </p>
            </section>
            
            <hr class="border-slate-200 my-8">

            <!-- Final Thoughts -->
            <section>
                <h2>Final Thoughts</h2>
                <p class="text-slate-600 leading-relaxed">
                    This project was an exercise in letting the data, and the audience's reaction to it, guide the narrative. It evolved from a simple country analysis into a more complex and honest regional story. The process was a powerful reminder that the first version of a data story is rarely the best one. The cycle of prototyping, gathering feedback, and iterating was what ultimately sharpened the argument and built a more credible final product.
                </p>
                <p class="mt-4 text-slate-600 leading-relaxed">
                    If I were to continue this work, the next step would be a formal econometric analysis to attempt to quantify the impact of migration while controlling for other factors. However, for the scope of this project, I'm proud to have created a visual story that presents a compelling association, remains transparent about its limitations, and contributes a clear, data-driven perspective to an important economic conversation in the region.
                </p>
            </section>

        </main>
        
        <!-- Footer -->
        <footer class="text-center text-sm text-slate-500 mt-12">
             <h3 class="font-semibold text-slate-600 mb-2">AI Acknowledgement</h3>
             <p>Throughout this project, AI was a valuable partner for brainstorming narrative flows, refining complex sentences, and articulating my reflections in these journal entries. While all core analysis, data work, and design choices were my own, AI helped ensure the final text was clear, consistent, and well-structured.</p>
            <p class="mt-4">© 2024 Amirkhon Khamidov</p>
        </footer>

    </div>
</body>
</html>

