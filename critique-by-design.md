| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

## Critique by design & Redesign 
This project is a bit of a homecoming for me. I used to work at the Center for Economic Research and Reforms (CERR) in Uzbekistan, the very organization that published the chart I chose to redesign. When I saw it, I recognized an opportunity—not just to improve a visualization, but to showcase the new data storytelling skills I've developed since my time there. This journal documents my process of turning a familiar, data-rich chart into a clearer, more insightful story.

---
## Step one: the visualization
The first step is always about finding a spark—a visualization that's interesting but has room for improvement. It’s like being a scout looking for a diamond in the rough.

!(link-to-your-original-viz-image.jpg)
*Source: review.uz, Center for Economic Research and Reforms (CERR)*

When I first saw this chart, I felt a mix of intrigue and information overload. Having worked at CERR, I'm deeply familiar with this data and its importance. I knew its audience—policymakers, economists, and investors—and I felt a personal drive to help the underlying story connect with them more effectively. The original presentation, with bar charts crowding a map, felt chaotic. It was hard to see the big picture through all the visual noise. I knew instantly that a powerful story was buried in there, and I chose this visualization because I was excited by the challenge of digging it out.

---
## Step two: the critique
This is the deconstruction phase—taking the original visualization apart to understand its strengths, weaknesses, and most importantly, its core message.

My first question wasn't "what's wrong with this chart?" but rather, "what's the most interesting story this data is trying to tell?" After extracting the numbers, I had an "aha!" moment. While every region was growing compared to the previous year, several were actually declining compared to the previous month. This conflict—strong long-term growth hiding pockets of short-term weakness—was the narrative hook.

This insight became my guiding star for the entire redesign. Formal methods like Stephen Few's profile were useful for diagnosing specific issues like label clutter, but the *"Good Charts"* principle of finding the core message was what truly set the direction. The original chart was trying to say everything at once; my goal was now to tell one compelling story about that divergence.

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
---
## Step five: build the solution

This was the most satisfying part: assembling all the pieces—the story, the layout, and the user feedback—into a finished, interactive product. The final solution, built with Datawrapper, directly addresses the issues found in the original visualization and incorporates the insights from the entire design process.

**Final Redesigned Visualization:**
<iframe title="Where is Business Activity Growing Fastest In Uzbekistan?" aria-label="Choropleth map" id="datawrapper-chart-38tGg" src="https://www.datawrapper.de/_/38tGg/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="635" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r,i=0;r=e[i];i++)if(r.contentWindow===a.source){var d=a.data["datawrapper-height"][t]+"px";r.style.height=d}}})}();
</script>


Overall, we see the following changes.

- The **narrative title** ("Where is Business Activity Growing Fastest In Uzbekistan?") and **descriptive subtitle** immediately frame the core question and the precise time frame.
- The **clean choropleth design** with an intuitive color scale allows for instant comparison between regions, a task that was difficult in the original.
- The inclusion of **major region labels** helps orient the viewer and makes the geographic data more accessible.
- The **explanatory note** at the bottom provides the crucial context about the index's components that my user testing revealed was missing.

Ultimately, this project was more than just an academic exercise. It was a way for me to reconnect with my past work and apply my new skills in a context I care about deeply. My goal was to create something that my former colleagues at CERR could find valuable—a visualization that not only presents data but also communicates a clear, actionable insight. It represents my growth as a designer and my continued passion for making complex economic data accessible and understandable.


---
## References
- Center for Economic Research and Reforms. "V Uzbekistane nablyudayetsya znachitelny rost indeksa delovoy aktivnosti" [Uzbekistan sees significant growth in the business activity index]. *review.uz*, Accessed September 18, 2025.

---
## AI acknowledgements
Throughout this project, I worked with Google's Gemini as a creative and analytical partner. I used it to brainstorm alternative design concepts, extract data from the original charts, refine the narrative for my titles, and help articulate my reflections and insights for this journal.




## Step one

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

_Include link to the original data visualization (or screenshot - make sure to correctly cite your sources, etc.).  Include paragraph or two on why you selected this particular data visualization.  For obvious reasons, the data visualization you select should come from a publicly accessible source._

## Step two: the critique
_Don't forget to complete the Google Form found on the assignment page.  You can summarize your thoughts here._

## Step three: Sketch a solution

## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._


| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|          |             |             |
|          |             |             |
|          |             |             |

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

