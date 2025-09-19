| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

## Critique by design & Redesign 
This project is a bit of a homecoming for me. I used to work at the Center for Economic Research and Reforms (CERR) in Uzbekistan, the very organization that published the chart I chose to redesign. When I saw it, I recognized an opportunity, not just to improve a visualization, but to showcase the new data storytelling skills I've developed since my time there. This journal documents my process of turning a familiar, data-rich chart into a clearer, more insightful story.

---
## Step one: the visualization

This visualization is from an article by Uzbekistan's Center for Economic Research and Reforms (CERR), an organization where I used to work. It was published as part of a regular economic update for policymakers, analysts, and the public.

<div style="width: 80%; margin: 20px auto; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden;">
    <div style="min-height:635px" id="datawrapper-vis-38tGg"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/38tGg/embed.js" charset="utf-8" data-target="#datawrapper-vis-38tGg"></script><noscript><img src="https://static.review.uz/uploads/1/1100__Y9DyU1IbE9sY2s1D_v2eqxrwvin2DCGw.jpg" " style="width:100%; height:auto; display:block;" /></noscript></div>
</div>
*Source: Economic Review, Center for Economic Research and Reforms (CERR), https://review.uz/en/post/v-uzbekistane-nablyudaetsya-znachitelny-rost-indeksa-delovoy-aktivnosti*

The map's primary goal is ambitious: it wants to show two different stories at once for every region in the country. First, it shows the short-term, **month-on-month change** in the Business Activity Index (represented by the orange bars). Second, it displays the long-term, **year-on-year change** (the purple bars). It attempts to do this by superimposing 28 different data points and their corresponding bar charts directly onto a geographic map of Uzbekistan.

While the chart is rich with information, the method of layering bars over the map creates a high cognitive load for the viewer. It's difficult to quickly compare regions or grasp the overarching story. I felt a personal drive to untangle this data and help the powerful underlying narrative connect more effectively with its intended audience.

When I first saw this chart, I felt a mix of intrigue and information overload. Having worked at CERR, I'm deeply familiar with this data and its importance. I knew its audience, policymakers, economists, and investors. While the chart is rich with information, the method of layering bars over the map creates a high cognitive load for the viewer. It's difficult to quickly compare regions or grasp the overarching story. I felt a personal drive to untangle this data and help the powerful underlying narrative connect more effectively with its intended audience. Plus, this is nice opportunity to showcase my upgraded skills to my colleagues at CERR. 


---
## Step two: the critique
**What Worked (The Positive Aspects):**

The visualization's greatest strength is its use of a map to provide **immediate geographic context**. It successfully answers the fundamental "where" question, which is critical for any regional analysis. It's also **data-rich**; it doesn’t oversimplify and provides two distinct, important metrics for every region, giving a comprehensive, if dense, overview.

**What Didn't Work (The Negative Aspects):**

Despite its strengths, the design's effectiveness is undermined by a few key issues:
- **Visual Clutter & High Cognitive Load:** The primary weakness is layering 28 data points and two bars per region onto a single map. This creates a chaotic visual field that forces the viewer to work hard to extract information. It violates a core heuristic of minimizing extraneous cognitive load.
- **Difficulty of Comparison:** The layout makes it incredibly difficult to compare regions. A viewer can't easily contrast the yearly growth in Kashkadarya with that in Karakalpakstan because their eyes have to jump across the map, find the correct purple bar, and read the corresponding number. This makes spotting trends and patterns a chore rather than an insight.
- **The Narrative is Buried:** The most interesting insight I found in the data—the conflict between strong yearly growth and weak monthly figures in several regions—is not immediately apparent. The visualization presents a database of facts but doesn't guide the viewer to the most important story.

To formalize my critique, I assessed the visualization against several key criteria from Stephen Few’s profile. Here's a summary of my thoughts:

Usefulness. The data is clearly useful for its intended audience such as decision makers, economists, and policymakers, because it shows how regions compare in terms of business activity.

Completeness. The visualization includes comparisons both to the previous month and to the same month of the previous year, which adds valuable context. Still, without extra reference points like national averages or trend lines, it feels slightly incomplete.

Perceptibility. While the bars are placed on the map correctly, the double bars for each region are sometimes hard to compare because of overlapping colors and uneven spacing. A simpler design could improve readability.

Truthfulness. The visualization represents the data accurately, with no misleading scales or distortions. Each bar matches the numbers shown, which maintains validity.

Intuitiveness. The idea of using a map plus bars is familiar, but the legend and double-color coding may require a moment to understand. For someone not used to this style, it may take effort at first.

Aesthetics. The map and bars are not ugly, but they are also not especially attractive. The color choices feel functional but not appealing. A cleaner, more modern design could make it more enjoyable to look at.

Engagement. The visualization draws the viewer in enough to scan regions and compare, but it does not really invite deeper exploration. More interactivity or clearer highlights could make it more engaging.

---
### Comparing Critique Methods

For this critique, I blended two approaches. The Data Visualization Effectiveness Profile from Stephen Few, was useful for a technical breakdown. It gave me the vocabulary to describe *why* the clutter was a problem (like creating cognitive load). It was systematic and rigorous.

However, the **"Good Charts" method** by Scott Berinato was more strategic. It pushed me to ask, "What is the *point* of this chart? Is it declarative or exploratory?", "What is the context?" and so on. This method was less about a checklist and more about finding the core communicative goal.

---
## Step three: Sketch a solution
With a clear story in mind, the next step was to imagine the best possible stage for it to be told on. This is the creative, "what if?" phase.

I considered a few different formats. A scatter plot could show the relationship between monthly and yearly change, but it would lose the crucial geographic context. A slope chart could highlight the divergence, but again, the map would be gone. The geography felt essential to the story.

The breakthrough came with a simple but powerful idea: give each metric its own canvas. I sketched out a **dual-map layout**, one for the year-on-year story of universal growth, and another for the more nuanced month-on-month story of a mixed economy. This "small multiples" approach felt like the perfect solution. It would declutter the view, retain the map, and allow the user to easily compare the two patterns. My "sketch" wasn't a detailed drawing, but a clear structural plan for telling my story with clarity.

!(link-to-your-sketch-image.jpg)
*My conceptual sketch, focusing on separating the two key narratives onto their own maps for clarity.*

---
---
## Step four: Test the solution
It's easy to fall in love with your own ideas, so this step was about a crucial reality check. Rather than just testing a static sketch, I decided to build an interactive prototype in Datawrapper. This allowed me to get much richer feedback on the user experience, not just the visual layout. I showed this interactive map to two peers to see if the design was as intuitive as I hoped.

**Questions Asked:**
- Can you tell me what you think this is?
- What is the main story or comparison you see here?
- Is there anything you find confusing or anything you feel is missing?
- Who do you think this is for?
- What would you change?

**Results:**

| Question | Interviewee 1 (Policy Analyst, late 20s) | Interviewee 2 (Journalism Student, early 20s) |
|---|---|---|
| **What is this about?** | "It's a comparison of economic activity in Uzbekistan, broken down by month and year for different regions." | "Looks like it's showing how business is changing across the country, comparing recent change to the annual trend." |
| **What's the main story?** | "The yearly growth looks strong everywhere, but the monthly map would show a more mixed picture. The separation makes that easy to see." | "That some places are growing a lot faster year-on-year than others. The side-by-side view helps compare the patterns." |
| **Anything confusing/missing?** | "No, it's very clear. I'd want the exact date range in a subtitle. And what exactly is the 'Business Activity Index'?" | "The colors make sense, but what do they mean? Like, what are they measuring?" |
| **Who is the audience?** | "Policymakers, economists, maybe investors." | "Journalists, researchers, anyone interested in the Uzbek economy." |
| **What would you change?** | "Add a subtitle with the specific time frame and source. Maybe a small note defining the index." | "Maybe add a little box explaining what the index is made of." |

**Synthesis:**

The feedback was a powerful reminder that **context is king**. While both interviewees immediately understood the purpose of the dual-map layout, their feedback revealed a clear demand for more context. They needed to know the specific time frame and, crucially, what the index was actually made of. This insight was invaluable; it showed me that I needed to move beyond just visualizing the numbers and provide the context required for true understanding. This led me to add a detailed subtitle and an explanatory note to the final design.

---
## Step five: build the solution

This was the final part: assembling all the pieces—the story, the layout, and the user feedback—into a finished, interactive product. The final solution, built with Datawrapper, directly addresses the issues found in the original visualization and incorporates the insights from the entire design process.


**Final Redesigned Visualization:**
<div style="width: 80%; margin: 20px auto; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden;">
    <div style="min-height:635px" id="datawrapper-vis-38tGg"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/38tGg/embed.js" charset="utf-8" data-target="#datawrapper-vis-38tGg"></script><noscript><img src="https://datawrapper.dwcdn.net/38tGg/full.png" alt="Where is Business Activity Growing Fastest In Uzbekistan? (Choropleth map)" style="width:100%; height:auto; display:block;" /></noscript></div>
</div>
*My final redesigned map. It aims for clarity and narrative focus, directly addressing the clutter of the original.*


The original chart’s biggest problem was its visual clutter, which buried the story. To solve this, I chose a clean **choropleth map** as the foundation, allowing me to focus on a single, powerful narrative: the year-on-year growth. The confusing and overlapping bar charts are gone, replaced by an intuitive **color scale** that makes regional comparisons effortless.

The user feedback in Step Four was a clear signal that context was missing. That's why I moved beyond just the data and focused on framing the narrative. The final visualization leads with a **strong, question-based title** and a **descriptive subtitle** so the viewer understands the core story before they even examine the details. The **explanatory note** at the bottom directly answers the question, "What is the Business Activity Index?", making the chart more self-sufficient and valuable—a direct result of the feedback I received.

Ultimately, this project was a way for me to reconnect with my past work and apply my new skills in a context I care about deeply. My goal was to create something that my former colleagues at CERR could find valuable—a visualization that not only presents data but also communicates a clear, actionable insight. 


---
## References
- Center for Economic Research and Reforms. "Uzbekistan Sees Significant Growth in the Business Activity Index". Rettrieved from: https://review.uz/en/post/v-uzbekistane-nablyudaetsya-znachitelny-rost-indeksa-delovoy-aktivnosti.


---
## AI acknowledgements
Throughout this project, I worked with AI as a creative and assistive partner. I used it to generate layout for my webpage, extract data from the original charts and help fix grammar of my reflections and insights for this journal.

