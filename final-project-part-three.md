
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
            color: #1e2b3b; /* slate-900 */
            margin-bottom: 1.5rem; /* mb-6 */
            margin-top: 2.5rem; /* mt-10 */
        }
        .content-body h3 {
            font-size: 1.5rem; /* 2xl */
            font-weight: 700;
            color: #1e2b3b; /* slate-900 */
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
            <h1 class="text-4xl font-bold text-slate-900 mb-6 text-center">Final Project: Part 3</h1>
            
            <!-- Final Story -->
            <section>
                <h2>The Final Data Story</h2>
                <p class="text-slate-600 leading-relaxed mb-4">
                    My final story, "Housing Price Growth in Uzbekistan," examines the significant increase in the country's housing prices from 2022 to 2024. The narrative explores the link between the influx of Russian migrants and the price spike, placing the trend within a regional context and considering other economic drivers to provide a balanced account.
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
                    The user feedback from Part II served as a guide for the final project. The changes improved the clarity, focus, and overall narrative flow of the story.
                </p>
                <ul class="list-disc list-inside space-y-4 mt-4 text-slate-600 leading-relaxed">
                    <li><strong>Refined the Core Visual.</strong> Based on feedback, I added a bar chart to the line chart to more clearly show the average annual growth in housing prices. This combination makes the unusual growth in 2022 and 2023 clear and provides a strong narrative hook.</li>
                    <li><strong>Established a Logical Narrative Sequence.</strong> The story was restructured to follow a clear, investigative path. It begins with the core finding in Uzbekistan, broadens to provide regional context with Kazakhstan and Kyrgyzstan, introduces the migration data as a potential cause, and finally examines other domestic factors. This sequence creates a logical flow that guides the audience from the "what" to the "why."</li>
                    <li><strong>Improved Visual Storytelling.</strong> I focused on making the transitions between sections in Shorthand feel seamless. Each visual builds on the last, creating a smooth movement from one part of the story to the next. For example, the colors used for each country are kept consistent across different charts, helping the audience track the information easily.</li>
                    <li><strong>Simplified the Narrative.</strong> The feedback on the "Supply and Demand Factors" section was that it was dense. I pruned it to the four most critical economic factors. This retained the analytical depth while making the story more focused and digestible for a time-constrained policy audience.</li>
                </ul>
            </section>

            <hr class="border-slate-200 my-8">

            <!-- Audience -->
            <section>
                 <h2>The Audience</h2>
                 <p class="text-slate-600 leading-relaxed">
                    The primary audience for this project is a specific persona: a busy policymaker or senior analyst within a government agency like Uzbekistan's Ministry of Economy and Finance or Ministry of Construction and Housing. This individual is highly knowledgeable about the local economy but is also extremely time-constrained. They need to quickly grasp the core issue, understand the key drivers, and trust the credibility of the information presented.
                 </p>
                 <p class="mt-4 text-slate-600 leading-relaxed">
                    Several key decisions were made with this audience persona in mind:
                 </p>
                 <ul class="list-disc list-inside space-y-3 mt-4 text-slate-600 leading-relaxed">
                    <li>The story was designed with clear, hierarchical headers and a 'scrollytelling' format that presents one key idea at a time. This respects the audience's limited time and allows them to absorb the main points quickly.</li>
                    <li> Knowing this audience would be skeptical of a single explanation, the "Supply and Demand Factors" section was included to demonstrate analytical rigor. By showing that other domestic variables were considered and found to be following stable trends, the story builds credibility and focuses attention on the migration anomaly.</li>
                    <li>The final visuals prioritize immediate comprehension. Complex chart types were avoided in favor of simple, direct bar and line charts, ensuring the message could be understood in seconds.</li>
                 </ul>
            </section>
            
            <hr class="border-slate-200 my-8">

            <!-- Design Decisions -->
            <section>
                 <h2>Summary: Final Design Decisions</h2>
                 <p class="text-slate-600 leading-relaxed">
                    This project was an end-to-end exercise in data storytelling, beginning with a broad question and culminating in a focused, audience-centric narrative. The core work involved gathering and cleaning disparate data sources, identifying a central thesis, and iteratively refining the visuals and narrative based on user feedback. The final design decisions were crucial in translating the complex analysis into a clear and compelling story.
                 </p>
                 <p class="mt-4 text-slate-600 leading-relaxed">
                    Key design choices included:
                 </p>
                 <ul class="list-disc list-inside space-y-4 mt-4 text-slate-600 leading-relaxed">
                    <li> The decision to combine a line chart with a bar chart was central. The line chart provides the essential historical context, showing the relatively stable trend before 2022. The bar chart delivers the analytical punch, quantifying the magnitude of the 2022-2023 spike. This dual approach allows the visual to serve both a quick, high-level summary and a more detailed examination. The bars for the key years were given a distinct, saturated color to immediately draw the eye to the core finding.</li>
                    <li> To connect the price spike to external events, I added vertical markers on the line chart for the first and second waves of Russian mobilization. This is a powerful storytelling technique that moves beyond simply stating a fact in the text. It creates an immediate, intuitive visual link between the external shock and the market's reaction, effectively 'showing' the correlation instead of just 'telling' it.</li>
                    <li> A consistent color palette was used to aid comprehension. Each country was assigned a specific, colorblind-safe color that was used in every chart, reducing cognitive load and making it easy to follow each country's data across different visualizations. The overall aesthetic was professional and clean, using a sans-serif font for readability and ample white space to ensure the charts were uncluttered and the story felt credible and authoritative for its policy-focused audience.</li>
                 </ul>
            </section>
            
            <hr class="border-slate-200 my-8">
            
            <!-- Reflections -->
            <section>
                <h2>Key Learnings</h2>
                <p class="text-slate-600 leading-relaxed">
                    This project was a valuable learning experience in applied data storytelling. It taught me the importance of moving beyond just creating charts to building a coherent narrative that guides an audience through a complex topic. The process of starting with a single-country focus and expanding it based on feedback was a practical lesson in analytical flexibility.
                </p>

                <h3>Challenges</h3>
                <p class="text-slate-600 leading-relaxed">
                    One of the main challenges was sourcing perfectly comparable data across three different countries. National statistics offices often have slightly different methodologies, which required careful data cleaning and a focus on relative trends rather than absolute values. Another challenge was deciding what information to leave out. It was tempting to include every data point, but the feedback from Part II was crucial in helping me focus on the core narrative for the intended audience.
                </p>

                <h3>Looking Forward</h3>
                <p class="text-slate-600 leading-relaxed">
                    This project has solidified my interest in using data visualization for policy communication. I plan to continue building on these skills, particularly in creating tools that allow policymakers to explore data themselves. The ability to translate complex analysis into a clear, visual story is a skill I will carry with me into my future career. I am very thankful for this course, as it provided a structured framework for thinking about data storytelling not just as a technical exercise, but as a critical communication tool.
                </p>
            </section>

            <hr class="border-slate-200 my-8">

            <!-- References -->
            <section>
                <h2>References</h2>
                <div class="text-slate-600 leading-relaxed space-y-2 text-sm">
                    <p>Institute for Macroeconomic and Regional Studies. (2023). *The impact of relocation on the economy of Uzbekistan*. IMRS. Retrieved from https://imrs.uz/publications/articles-and-abstracts/impact_on_economy</p>
                    <p>Federal State Statistics Service (Rosstat). (2023). *Socio-economic situation of Russia*. Rettrieved from https://rosstat.gov.ru/statistic)</p>
                    <p>State Committee of the Republic of Uzbekistan on Statistics (Stat.uz). (n.d.). *Housing market prices*. Retrieved from https://stat.uz/en/official-statistics/prices-and-indexes</p>
                </div>
            </section>

        </main>
        
        <!-- Footer -->
        <footer class="text-center text-sm text-slate-500 mt-12">
             <h3 class="font-semibold text-slate-600 mb-2">AI Acknowledgement</h3>
             <p>Throughout this project, AI was a valuable partner for brainstorming narrative flows, refining complex sentences, and articulating my reflections in these journal entries. While all core analysis, data work, and design choices were my own, AI helped ensure the final text was clear, consistent, and well-structured.</p>
            <p class="mt-4">© 2025 Amirkhon Khamidov</p>
        </footer>

    </div>
</body>
</html>

