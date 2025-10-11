
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amirkhon Khamidov | Data & Policy Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Simple animation for cards on hover */
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
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
                <ul class="flex justify-center space-x-4 sm:space-x-6">
                    <li><a href="./" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Home</a></li>
                    <li><a href="#" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Data Viz Examples</a></li>
                    <li><a href="#" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Critique by Design</a></li>
                    <li><a href="#" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project</a></li>
                </ul>
            </nav>
        </header>

        <hr class="border-slate-200 mb-10">

        <!-- About Me Section -->
        <section id="about" class="mb-12 bg-white p-8 rounded-xl shadow-md border border-slate-200">
            <div class="flex flex-col md:flex-row items-center gap-8">
                <div class="md:w-3/4">
                    <h2 class="text-3xl font-bold text-slate-900 mb-4">About Me</h2>
                    <p class="mb-3">Hi! I’m <strong>Amirkhon Khamidov</strong> (he/him), a Master of Public Policy & Management candidate at Carnegie Mellon University’s Heinz College.</p>
                    <p class="mb-3">My background is in economics, policy research, and teaching. I’ve worked at think tanks and universities on projects ranging from industrial policy to education reform. I enjoy turning complex datasets into clear, accessible insights that support better decision-making.</p>
                    <p class="mb-4">Beyond academics, I’m passionate about connecting people and ideas, and building collaborations between research, policy, and practice.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="bg-slate-800 text-white py-2 px-4 rounded-lg hover:bg-slate-700 transition-colors">LinkedIn</a>
                        <a href="#" class="bg-slate-800 text-white py-2 px-4 rounded-lg hover:bg-slate-700 transition-colors">GitHub</a>
                        <a href="#" class="bg-slate-800 text-white py-2 px-4 rounded-lg hover:bg-slate-700 transition-colors">Email</a>
                    </div>
                </div>
                <div class="md:w-1/4 flex-shrink-0">
                    <img src="https://placehold.co/400x400/E2E8F0/475569?text=AK" alt="Amirkhon Khamidov" class="rounded-full w-40 h-40 object-cover border-4 border-white shadow-lg mx-auto">
                </div>
            </div>
        </section>

        <!-- My Work Section -->
        <section id="work" class="mb-12">
            <h2 class="text-3xl font-bold text-slate-900 mb-6 text-center">My Work</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                
                <!-- Project Card 1 -->
                <div class="project-card bg-white p-6 rounded-xl shadow-md border border-slate-200 transition-all duration-300">
                    <h3 class="text-2xl font-bold text-slate-900 mb-2">Critique by Design</h3>
                    <p class="text-slate-600 mb-4">A redesign exercise focused on improving a cluttered chart about Uzbekistan's economic activity.</p>
                    <a href="#" class="font-semibold text-blue-600 hover:underline">→ Read the full journal entry</a>
                </div>

                <!-- Project Card 2 -->
                <div class="project-card bg-white p-6 rounded-xl shadow-md border border-slate-200 transition-all duration-300">
                    <h3 class="text-2xl font-bold text-slate-900 mb-2">Data Viz Examples</h3>
                    <p class="text-slate-600 mb-4">A curated gallery of data visualizations that I admire and an analysis of why they are effective.</p>
                    <a href="#" class="font-semibold text-blue-600 hover:underline">→ View the gallery</a>
                </div>

                <!-- Project Card 3 -->
                <div class="project-card bg-white p-6 rounded-xl shadow-md border border-slate-200 transition-all duration-300 col-span-1 md:col-span-2">
                    <h3 class="text-2xl font-bold text-slate-900 mb-2">Final Project</h3>
                    <p class="text-slate-600 mb-4">The complete process for my final project, from the initial proposal and audience analysis to the final deliverable.</p>
                    <ul class="list-disc list-inside space-y-2">
                        <li><a href="#" class="font-semibold text-blue-600 hover:underline">Part I: Proposal & Audience Analysis</a></li>
                        <li><a href="#" class="font-semibold text-blue-600 hover:underline">Part II: Data & Prototype</a></li>
                        <li><a href="#" class="font-semibold text-blue-600 hover:underline">Part III: Final Visualization</a></li>
                    </ul>
                </div>
            </div>
        </section>

        <hr class="border-slate-200 my-10">

        <!-- Course Goals & Reflections -->
        <section id="goals" class="mb-12">
            <h2 class="text-3xl font-bold text-slate-900 mb-4 text-center">Course Goals & Reflections</h2>
            <div class="bg-white p-8 rounded-xl shadow-md border border-slate-200">
                <p class="mb-4">In this course, "Telling Stories with Data," my primary goal was to bridge the gap between raw data and actionable insight. I focused on:</p>
                <ol class="list-decimal list-inside space-y-2 text-slate-700">
                    <li><strong>Strengthening storytelling skills</strong> — Learning to match visuals to the decisions audiences need to make.</li>
                    <li><strong>Improving design choices</strong> — Mastering color, accessibility, chart selection, and clarity.</li>
                    <li><strong>Building reproducible workflows</strong> — Ensuring every chart is backed by code and can be updated easily.</li>
                    <li><strong>Publishing interactives</strong> — Creating lightweight, web-ready pieces to share in a portfolio.</li>
                    <li><strong>Practicing critique and iteration</strong> — Improving work by learning from peers and giving constructive feedback.</li>
                </ol>
                <p class="mt-4 italic">After graduation, I hope to work in policy research and government, using visualization to bring evidence to life for leaders and citizens.</p>
            </div>
        </section>

        <!-- AI Acknowledgement -->
        <footer class="text-center text-sm text-slate-500">
             <h3 class="font-semibold text-slate-600 mb-2">AI Acknowledgement</h3>
            <p>I utilized AI tools as a writing assistant to help proofread content, refine sentence structure, and ensure the Markdown syntax was clean and effective. All core concepts, analysis, and designs are my own.</p>
            <p class="mt-4">© 2024 Amirkhon Khamidov</p>
        </footer>

    </div>

</body>
</html>
