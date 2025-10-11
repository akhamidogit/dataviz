
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Critique by Design | Amirkhon Khamidov's Portfolio</title>
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
                    <li><a href="critique-by-design.html" class="text-blue-600 font-bold transition-colors">Critique by Design</a></li>
                    <li><a href="final-project-part-one.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project I</a></li>
                    <li><a href="final-project-part-two.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project II</a></li>
                    <li><a href="final-project-part-three.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project III</a></li>
                </ul>
            </nav>
        </header>

        <hr class="border-slate-200 mb-10">

        <!-- Main Content Area -->
        <main class="bg-white p-6 sm:p-8 rounded-xl shadow-md border border-slate-200 content-body">
            <h1 class="text-4xl font-bold text-slate-900 mb-6 text-center">Critique by Design & Redesign</h1>
            <p class="text-slate-600 text-lg leading-relaxed">
                This project is a bit of a homecoming for me. I used to work at the Center for Economic Research and Reforms (CERR) in Uzbekistan, the very organization that published the chart I chose to redesign. When I saw it, I recognized an opportunity, not just to improve a visualization, but to showcase the new data storytelling skills I've developed since my time there. This journal documents my process of turning a familiar, data-rich chart into a clearer, more insightful story.
            </p>
            
            <hr class="border-slate-200 my-8">

            <!-- Step One -->
            <section>
                <h2>Step One: The Visualization</h2>
                <p class="mb-6 text-slate-600 leading-relaxed">This visualization is from an article by Uzbekistan's Center for Economic Research and Reforms (CERR), an organization where I used to work. It was published as part of a regular economic update for policymakers, analysts, and the public.</p>
                <figure class="text-center">
                    <img src="https://static.review.uz/uploads/1/1100__Y9DyU1IbE9sY2s1D_v2eqxrwvin2DCGw.jpg" alt="Business Activity Visualization" class="max-w-full sm:max-w-[70%] mx-auto border border-slate-200 rounded-lg p-1 bg-slate-50 shadow-sm">
                    <figcaption class="mt-2 text-sm text-slate-500 italic">Source: Economic Review, CERR</figcaption>
                </figure>
                <p class="mt-6 text-slate-600 leading-relaxed">The map's primary goal is ambitious: it wants to show two different stories at once for every region in the country. First, it shows the short-term, <strong>month-on-month change</strong> in the Business Activity Index (represented by the orange bars). Second, it displays the long-term, <strong>year-on-year change</strong> (the purple bars). While the chart is rich with information, the method of layering bars over the map creates a high cognitive load for the viewer. It's difficult to quickly compare regions or grasp the overarching story. I felt a personal drive to untangle this data and help the powerful underlying narrative connect more effectively with its intended audience.</p>
            </section>

            <!-- Step Two -->
            <section>
                <h2>Step Two: The Critique</h2>
                <h3 class="!mt-4">What Worked (The Positive Aspects):</h3>
                <p class="text-slate-600 leading-relaxed">The visualization's greatest strength is its use of a map to provide <strong>immediate geographic context</strong>. It successfully answers the fundamental "where" question, which is critical for any regional analysis. It's also <strong>data-rich</strong>; it doesn’t oversimplify and provides a comprehensive, if dense, overview.</p>
                
                <h3 class="mt-6">What Didn't Work (The Negative Aspects):</h3>
                <ul class="list-disc list-inside space-y-2 text-slate-600 leading-relaxed">
                    <li><strong>Visual Clutter & High Cognitive Load:</strong> The primary weakness is layering 28 data points and two bars per region onto a single map. This creates a chaotic visual field that forces the viewer to work hard to extract information.</li>
                    <li><strong>Difficulty of Comparison:</strong> The layout makes it incredibly difficult to compare regions. A viewer can't easily contrast the yearly growth in one area with another because their eyes have to jump across the map.</li>
                    <li><strong>The Narrative is Buried:</strong> The most interesting insight—the conflict between strong yearly growth and weak monthly figures in several regions—is not immediately apparent.</li>
                </ul>
            </section>
            
            <!-- Step Three -->
            <section>
                <h2>Step Three: Sketch a Solution</h2>
                <p class="text-slate-600 leading-relaxed mb-6">With a clear story in mind from my critique, my goal was to directly address the weaknesses: the visual clutter and the difficulty of comparison. I moved from data exploration to sketching out a clearer presentation.</p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center">
                    <div>
                        <img src="https://raw.githubusercontent.com/akhamidogit/dataviz/main/tg_image_7.png" alt="Data Table Sketch" class="w-full border border-slate-200 rounded-lg p-1 bg-slate-50 shadow-sm">
                        <p class="mt-2 text-sm text-slate-500 italic"><b>1. Data Extraction:</b> First, I pulled all the numbers into a simple table to see the data clearly.</p>
                    </div>
                     <div>
                        <img src="https://raw.githubusercontent.com/akhamidogit/dataviz/main/sketch%201.jpg" alt="Structural Sketch" class="w-full border border-slate-200 rounded-lg p-1 bg-slate-50 shadow-sm">
                        <p class="mt-2 text-sm text-slate-500 italic"><b>2. Structural Sketch:</b> Next, I sketched a rough layout, focusing on hierarchy and clear sections.</p>
                    </div>
                     <div>
                        <img src="https://raw.githubusercontent.com/akhamidogit/dataviz/main/sketch%202.jpg" alt="Choropleth Map Sketch" class="w-full border border-slate-200 rounded-lg p-1 bg-slate-50 shadow-sm">
                        <p class="mt-2 text-sm text-slate-500 italic"><b>3. The Chosen Direction:</b> This sketch became my redesign, using a clean choropleth map for intuitive comparison.</p>
                    </div>
                </div>
            </section>

            <!-- Step Four -->
            <section>
                <h2>Step Four: Test the Solution</h2>
                <p class="text-slate-600 leading-relaxed mb-6">I built an interactive prototype in Datawrapper and showed it to three peers to see if the design was as intuitive as I hoped. The feedback was invaluable and formed a clear blueprint for my final design.</p>
                <h3 class="!mt-4">Synthesis & Redesign Plan</h3>
                <ol class="list-decimal list-inside space-y-2 text-slate-600 leading-relaxed">
                    <li><strong>The Year-on-Year Story is King:</strong> All three participants concluded that the year-on-year change was the most compelling narrative. This gave me the confidence to focus my final design exclusively on this single, powerful story.</li>
                    <li><strong>Context is Non-Negotiable:</strong> Every participant asked for more context, like what the index measured and a clearer timeframe. This was a crucial reminder that a visualization must be self-sufficient.</li>
                </ol>
            </section>

            <!-- Step Five -->
            <section>
                <h2>Step Five: Build the Solution</h2>
                <p class="text-slate-600 leading-relaxed mb-6">This was the final part: assembling all the pieces into a finished, interactive product. The final solution, built with Datawrapper, directly addresses the issues found in the original visualization and incorporates the insights from the entire design process.</p>
                <h3 class="text-center !mt-4">Final Redesigned Visualization</h3>
                <div class="w-full my-4 border border-slate-200 rounded-lg overflow-hidden shadow-md">
                    <div id="datawrapper-vis-38tGg" style="min-height:635px">
                        <script type="text/javascript" defer src="https://datawrapper.dwcdn.net/38tGg/embed.js" charset="utf-8"></script>
                        <noscript><img src="https://datawrapper.dwcdn.net/38tGg/full.png" alt="Where is Business Activity Growing Fastest In Uzbekistan? (Choropleth map)"/></noscript>
                    </div>
                </div>
                <p class="text-slate-600 leading-relaxed mt-6">The original chart’s biggest problem was its visual clutter. I chose a clean <strong>choropleth map</strong>, allowing me to focus on a single, powerful narrative: year-on-year growth. The confusing bar charts are gone, replaced by an intuitive <strong>color scale</strong> that makes regional comparisons effortless. I also added a <strong>strong, question-based title</strong> and an <strong>explanatory note</strong> to provide the context that user feedback showed was missing.</p>
            </section>

        </main>

        <!-- Footer -->
        <footer class="text-center text-sm text-slate-500 mt-12">
             <h3 class="font-semibold text-slate-600 mb-2">AI Acknowledgement</h3>
            <p>Throughout this project, I worked with AI as a creative and assistive partner. I used it to generate layout for my webpage, extract data from the original charts and help fix grammar of my reflections and insights for this journal.</p>
            <p class="mt-4">© 2025 Amirkhon Khamidov</p>
        </footer>

    </div>
</body>
</html>

