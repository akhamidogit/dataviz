
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
                    <li><a href="final-project-part-one" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project I</a></li>
                    <li><a href="final-project-part-two" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project II</a></li>
                    <li><a href="final-project-part-three" class="text-blue-600 font-bold transition-colors">Final Project III</a></li>
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
                    The final story investigates the dramatic surge in Uzbekistan's housing prices from 2022 to 2024. It moves beyond a simple country-level analysis to place the trend in a regional context, comparing it with Kazakhstan and Kyrgyzstan. The narrative explores the compelling temporal link between the influx of Russian migrants and the price spike, while carefully examining other economic drivers to provide a balanced and nuanced perspective. The goal was to create a clear, credible, and visually engaging story for those interested in the region's economic dynamics.
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
                    The feedback from user research in Part II was instrumental in shaping the final narrative. The most significant change was fully committing to the <strong>regional story</strong>. Instead of treating Kazakhstan and Kyrgyzstan as secondary, I integrated them into the primary visuals from the start. This immediately addressed the feedback that a narrow, Uzbekistan-only focus felt incomplete.
                </p>
                <p class="mt-4 text-slate-600 leading-relaxed">
                    I also acted directly on the call for more historical context by extending the migration data back to 2019, which makes the 2022 spike far more dramatic and visually significant. To address concerns about causality, I added a persistent "Association, not causation" label to key charts and included a dedicated "Methods and Limitations" section in the final story. Finally, the "drivers wall" was streamlined to the four most critical factors, making it less overwhelming while still demonstrating that I had considered alternative explanations.
                </p>
            </section>

            <hr class="border-slate-200 my-8">

            <!-- Audience -->
            <section>
                 <h2>The Audience</h2>
                 <p class="text-slate-600 leading-relaxed">
                    My primary audience remained policy-minded graduate students and early-career analysts in fields like economics, public policy, and international affairs. This group is trained to question single-cause explanations and appreciate nuance. The user interviews confirmed this; they weren't just looking for a simple answer but wanted to see a structured argument.
                 </p>
                 <p class="mt-4 text-slate-600 leading-relaxed">
                    Several design decisions were made specifically for them. The inclusion of the "drivers wall" was a direct response to anticipating their skepticism. It shows that I've considered factors like income and population growth, which strengthens the credibility of the migration-as-a-catalyst theory. Similarly, the indexed line chart for prices was chosen because this audience understands its value for making fair cross-country comparisons. The explicit limitations section also respects their analytical training by openly stating the boundaries of the analysis.
                 </p>
            </section>
            
            <hr class="border-slate-200 my-8">

            <!-- Design Decisions -->
            <section>
                 <h2>Final Design Decisions</h2>
                 <p class="text-slate-600 leading-relaxed">
                    One of the most critical design decisions was using an **indexed line chart** for the regional price comparison. By setting a common baseline (Index = 100 in 2019), it allows the audience to compare the *rate of growth* across three countries with very different housing price levels, which was essential for telling a fair story.
                 </p>
                 <p class="mt-4 text-slate-600 leading-relaxed">
                    For the migration data, **small multiples** proved to be the most effective choice. Placing the three country charts side-by-side with a synchronized x-axis makes it incredibly easy to see that the migration spike in late 2022 was a shared regional event, but with different magnitudes. This visual structure does the heavy lifting of comparison for the reader. Finally, I focused on a clean, minimalist aesthetic with a colorblind-safe palette and direct labeling to minimize cognitive load and ensure the story, not the chart junk, was the focus.
                 </p>
            </section>
            
            <hr class="border-slate-200 my-8">

            <!-- Final Thoughts -->
            <section>
                <h2>Final Thoughts</h2>
                <p class="text-slate-600 leading-relaxed">
                    This project was a fascinating journey. It began as a straightforward analysis of a single country's housing market and evolved into a nuanced regional story about the interplay of migration and economics. The process reinforced how crucial iteration and user feedback are to effective data storytelling. Seeing the narrative sharpen and become more credible with each round of critique was easily the most exciting part of the process.
                </p>
                <p class="mt-4 text-slate-600 leading-relaxed">
                    If I had more time, I would have loved to dive deeper into econometric analysis to move beyond visual association toward more robust causal inference. A regression model could help quantify the impact of migration while controlling for the other drivers I explored visually. However, for the scope of this course, I'm proud of creating a data story that is honest about its limitations while still presenting a compelling, evidence-based narrative. I look forward to applying these skills in my future work, turning complex data into clear stories that can inform policy and public understanding.
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

