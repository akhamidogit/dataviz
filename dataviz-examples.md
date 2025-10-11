
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Viz Examples | Amirkhon Khamidov's Portfolio</title>
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
                    <li><a href="dataviz-examples.html" class="text-blue-600 font-bold transition-colors">Data Viz Examples</a></li>
                    <li><a href="critique-by-design.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Critique by Design</a></li>
                    <li><a href="final-project-part-one.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project I</a></li>
                    <li><a href="final-project-part-two.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project II</a></li>
                    <li><a href="final-project-part-three.html" class="text-slate-700 hover:text-blue-600 font-medium transition-colors">Final Project III</a></li>
                </ul>
            </nav>
        </header>

        <hr class="border-slate-200 mb-10">

        <!-- Main Content Area -->
        <main class="bg-white p-6 sm:p-8 rounded-xl shadow-md border border-slate-200 content-body">
            <h1 class="text-4xl font-bold text-slate-900 mb-6 text-center">Data Visualization Examples</h1>
            <p class="text-slate-600 text-lg leading-relaxed italic text-center">
                This page contains some of my data visualization examples from the course. Each visualization includes a brief explanation of what it shows and the data sources used.
            </p>
            
            <hr class="border-slate-200 my-8">

            <!-- Part 2 -->
            <section>
                <h2>Part 2: OECD Government Debt</h2>
                <p class="mb-6 text-slate-600 leading-relaxed">This chart shows the general government debt across all OECD countries, created as part of a course assignment.</p>
                
                <div class='tableauPlaceholder' id='viz1757307876350' style='position: relative; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);'>
                    <noscript>
                        <a href='#'><img alt='Gov Debt ' src='https://public.tableau.com/static/images/Go/GovernmentdebtacrossOECDcountries/Sheet1/1_rss.png' style='border: none' /></a>
                    </noscript>
                    <object class='tableauViz' style='display:none;'>
                        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
                        <param name='embed_code_version' value='3' /> 
                        <param name='site_root' value='' />
                        <param name='name' value='GovernmentdebtacrossOECDcountries/Sheet1' />
                        <param name='tabs' value='no' />
                        <param name='toolbar' value='yes' />
                        <param name='static_image' value='https://public.tableau.com/static/images/Go/GovernmentdebtacrossOECDcountries/Sheet1/1.png' /> 
                        <param name='animate_transition' value='yes' />
                        <param name='display_static_image' value='yes' />
                        <param name='display_spinner' value='yes' />
                        <param name='display_overlay' value='yes' />
                        <param name='display_count' value='yes' />
                        <param name='language' value='en-US' />
                    </object>
                </div>
                <script type='text/javascript'>
                    var divElement1 = document.getElementById('viz1757307876350');
                    var vizElement1 = divElement1.getElementsByTagName('object')[0];
                    if (divElement1.offsetWidth > 800) {
                        vizElement1.style.width = '100%';
                        vizElement1.style.height = (divElement1.offsetWidth * 0.5) + 'px';
                    } else if (divElement1.offsetWidth > 500) {
                        vizElement1.style.width = '100%';
                        vizElement1.style.height = (divElement1.offsetWidth * 0.5) + 'px';
                    } else {
                        vizElement1.style.width = '100%';
                        vizElement1.style.height = (divElement1.offsetWidth * 0.75) + 'px';
                    }
                    var scriptElement1 = document.createElement('script');
                    scriptElement1.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
                    vizElement1.parentNode.insertBefore(scriptElement1, vizElement1);
                </script>
            </section>

            <!-- Part 3 -->
            <section>
                <h2>Part 3: G7 Government Debt (Redesign)</h2>
                <p class="mb-6 text-slate-600 leading-relaxed">I redesigned the previous chart to focus only on the G7 countries. This version highlights a specific narrative: Japan has the highest government debt among the G7 nations.</p>

                <div class='tableauPlaceholder' id='viz1757389644915' style='position: relative; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);'>
                    <noscript>
                        <a href='#'><img alt='Japan remains the country to experience high Government Debt among G7 countries' src='https://public.tableau.com/static/images/Ja/Japan_17573896133640/GovDebt/1_rss.png' style='border: none' /></a>
                    </noscript>
                    <object class='tableauViz' style='display:none;'>
                        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
                        <param name='embed_code_version' value='3' /> 
                        <param name='site_root' value='' />
                        <param name='name' value='Japan_17573896133640/GovDebt' />
                        <param name='tabs' value='no' />
                        <param name='toolbar' value='yes' />
                        <param name='static_image' value='https://public.tableau.com/static/images/Ja/Japan_17573896133640/GovDebt/1.png' /> 
                        <param name='animate_transition' value='yes' />
                        <param name='display_static_image' value='yes' />
                        <param name='display_spinner' value='yes' />
                        <param name='display_overlay' value='yes' />
                        <param name='display_count' value='yes' />
                        <param name='language' value='en-US' />
                    </object>
                </div>
                <script type='text/javascript'>
                    var divElement2 = document.getElementById('viz1757389644915');
                    var vizElement2 = divElement2.getElementsByTagName('object')[0];
                     if (divElement2.offsetWidth > 800) {
                        vizElement2.style.width = '100%';
                        vizElement2.style.height = (divElement2.offsetWidth * 0.5) + 'px';
                    } else if (divElement2.offsetWidth > 500) {
                        vizElement2.style.width = '100%';
                        vizElement2.style.height = (divElement2.offsetWidth * 0.5) + 'px';
                    } else {
                        vizElement2.style.width = '100%';
                        vizElement2.style.height = (divElement2.offsetWidth * 0.75) + 'px';
                    }
                    var scriptElement2 = document.createElement('script');
                    scriptElement2.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
                    vizElement2.parentNode.insertBefore(scriptElement2, vizElement2);
                </script>
            </section>
        </main>

        <!-- Footer -->
        <footer class="text-center text-sm text-slate-500 mt-12">
            <p class="mt-4">© 2025 Amirkhon Khamidov</p>
        </footer>

    </div>
</body>
</html>

