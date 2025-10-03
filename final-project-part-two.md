| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes / storyboards

## Story outline and flow
My story centers on the sharp rise in **Uzbekistan’s housing prices (2022–2024)**. I want to explore whether the influx of **Russian migrants acted as a catalyst**, while also situating this trend in the **regional context** (Kazakhstan, Kyrgyzstan) and considering **other demand/supply factors**.

In Part I, my setup was relatively straightforward: housing prices in Uzbekistan surged sharply between 2022–2024, and my initial idea was to test whether the influx of Russian migrants could help explain this change. The basic sketches were focused on Uzbekistan only, showing a simple before-and-after comparison. That was the starting point of my story.

For Part II, I introduced the **conflict**: the problem with telling the story narrowly through Uzbekistan alone is that the audience quickly asks, “But what about the neighbors? What about Kazakhstan, which lies directly between Russia and Uzbekistan?” By keeping the lens too narrow, I risked presenting a monocausal or oversimplified narrative. Migration alone might look convincing, but without testing other possibilities — such as general economic growth, supply shortages, or parallel trends in nearby countries — the story lacks depth and balance. This is where the tension comes in: how do I expand the story without overwhelming it, and how do I distinguish correlation from causation?

The **resolution** I developed in Part II was to deliberately expand the storyline in two ways. First, I added a **regional layer** by incorporating Kazakhstan and Kyrgyzstan into my visuals. This gives readers a more holistic view of housing dynamics in Central Asia and shows whether Uzbekistan was unique or part of a shared trend. Second, I deepened the analysis by building a **drivers wall** of demand and supply factors — wages, population, building materials costs, and housing stock. This allows me to test whether these alternative explanations broke from historical patterns in 2022–2024. If they mostly track their prior trends, then migration can plausibly be framed as the catalyst that accelerated housing prices during that period.  

Together, this setup–conflict–resolution structure strengthens the narrative: I start by situating the price spike, highlight the problem of oversimplification, and then resolve it by broadening both geographic scope and explanatory factors. My storyboard now reflects this progression, guiding the reader step by step through context, conflict, and cautious resolution.

📍 You can view my evolving storyboard and draft visuals directly in **Shorthand** here: [Shorthand preview link](https://preview.shorthand.com/fmoJFGXger9iCo5F/responsive/desktop).


## Storyboard walkthrough
1. **Hook (Hero panel)** – “Housing prices in Uzbekistan rose X% since 2021.” Hypothesis: migration as catalyst.  
2. **Regional context** – Indexed price lines for Uzbekistan, Kazakhstan, Kyrgyzstan (2018–2025).  
3. **Migration flows** – Arrivals of Russian citizens to each country, showing the 2022 spike.  
4. **Alignment panel** – Side-by-side: migration spike vs. price path (with vertical guides).  
5. **Drivers wall** – Demand: real income, population. Supply: building materials, housing stock.  
6. **Quick tags** – “Tracks trend” vs. “Breakout” indicators.  
7. **Limits & methods note** – Clarify association ≠ causation.  
8. **Feedback invitation** – Prompt for user reactions.  

## Wireframe notes
- Layout: sequential Shorthand flow, one storyboard section per element.  
- Design: indexed scales, direct labels, colorblind-safe hues, legends on top.  
- Accessibility: ≥12px tick labels, annotations over tooltips, consistent x-axes.  

**What changed from Part I**: I expanded from a single-country story to a **regional lens**, and added a **drivers wall** to explore alternative explanations. The idea is to check if non-migration factors followed historical trends—if so, migration becomes the plausible “catalyst.”

---

# Design: Data Visuals (current state & iterations)

### Visual 1 — Regional Housing Price Index (2018–2025)
- **Type**: Indexed line chart (Index=100 at 2019).  
- **Why indexed**: enables cross-country comparison regardless of different price levels.  
- **Iteration**: v1 (Uzbekistan only) → v2 (added Kazakhstan, Kyrgyzstan) → v3 (added event annotations in late-2022; improved direct labeling; legend moved to top).  

### Visual 2 — Russian Migrant Arrivals (2019–2024)
- **Type**: Small multiples (3 mini line charts by country) or a stacked area with country toggles.  
- **Why**: clearer to see timing and relative magnitude of spikes; aligns with price timeline in the storyboard.  
- **Iteration**: v1 (single country) → v2 (three small multiples for side-by-side timing alignment) → v3 (consistent x-axis ticks; short annotations).  

### Visual 3 — “Drivers Wall” (Supply & Demand Factors)
- **Demand**: real income index; annual population/urbanization change.  
- **Supply**: building materials cost index; new housing units/stock.  
- **Type**: Four small-multiples line charts (uniform axes, same base year if indexed).  
- **Iteration**: v1 (mixed scales) → v2 (indexed, same time window) → v3 (badge tags: “breakout vs trend” / “tracks trend”).  

### Visual 4 — Alignment Snapshot (Side-by-Side)
- **Left**: migration spike timeline; **Right**: price path with the same vertical guides.  
- **Purpose**: a single glance to grasp temporal proximity (with an explicit “association, not causation” label).  
- **Iteration**: added thin guides and a caption explaining limits.  

---

# User research 

## Target audience
- **Primary**: policy-minded graduate students and early-career analysts.  
- **Secondary**: informed readers in Central Asia (homebuyers, journalists, civic analysts).  
- **Recruiting approach**: five participants – 2 policy peers, 2 general readers, 1 practitioner.  

## Interview script (detailed)
> I ran semi-structured interviews (~15–20 minutes). The goal was to test comprehension, timing interpretation, causality clarity, and reaction to the “drivers wall.” Below is the script:

1. **Warm-up** – “When you hear housing prices in Uzbekistan, what do you think are the main drivers?”  
2. **Story comprehension** – “Skim the first two sections—what’s the story so far in one sentence?”  
3. **Price trend** – “Point out when prices start rising the fastest. What might explain that?”  
4. **Migration flows** – “Look at the migration charts—what stands out, and when?”  
5. **Alignment** – “Compare the two—what relationship do you see?”  
6. **Drivers wall** – “Now scan these four extra charts—do you find them useful, or too much?”  
7. **Causality clarity** – “Do you feel I’m claiming causation, or just showing an association?”  
8. **Credibility** – “What would make you more confident in the story?”  
9. **Usability** – “Was anything confusing, unclear, or visually hard to follow?”  
10. **Close** – “On a scale of 1–5: story clarity, visual clarity, credibility. Why?”

## Interview findings
> Detail the findings from your interviews.  Do not include PII.  Capture specific insights where possible.

### Insights & quotes
1. **Regional context matters (4/5)**  
   > “If Kazakhstan sits between Russia and Uzbekistan, I immediately wonder what happened in Kazakhstan. You can’t skip that part.”  
   → Action: Keep all three countries upfront.  

2. **Migration flows need longer history (3/5)**  
   > “Show me the trend before 2022, otherwise I don’t know if this spike is unusual.”  
   → Action: Extend series to 2019–2024.  

3. **Causality caution (3/5)**  
   > “This looks like correlation. Please keep reminding me you’re not saying one causes the other.”  
   → Action: Persistent ‘Association, not causation’ badge.  

4. **Drivers wall mixed (3/5)**  
   > “Four is fine, more is too much for me.”  
   > “Actually, I’d trust you more if I saw *all* the drivers, even if messy.”  
   → Action: Four main drivers in-line, rest optional appendix.  

5. **Mobile readability**  
   > “On my phone, the labels are tiny.”  
   → Action: increase font sizes, simplify legends.  

| Questions | Interview 1 | Interview 2 | Interview 3 |
|-----------|-------------|-------------|-------------|
| “What’s the story so far?” | “Prices up, migration may be part of it.” | “Clear, but Kazakhstan is missing.” | “Got it, but too much on one slide.” |
| “What stands out in migration charts?” | 2022 spike obvious | Wanted more pre-2020 history | “Kazakhstan’s spike is sharpest.” |
| “Drivers wall useful?” | “Too dense.” | “Useful, shows other angles.” | “Pick top 4.” |
| “Causality?” | “Feels causal, needs caveat.” | “Add explicit disclaimer.” | “Association only, please.” |

---

# Identified changes for Part III
> Document the changes you plan on implementing next week to address any issues identified.  

| Research synthesis | Anticipated changes for Part III |
|--------------------|----------------------------------|
| Regional context important | Keep Uzbekistan/Kazakhstan/Kyrgyzstan comparison upfront, with Index=100 (2019). |
| Longer migration series needed | Extend migration flows to 2019–2024, highlight 2022 spike. |
| Clarify correlation vs causation | Add “Association, not causation” badge + limitations card. |
| Drivers wall balance | Prune to 4 key drivers (income, population, materials cost, housing stock), with badges (“tracks trend” vs “breakout”). |
| Conflicting feedback on density | Keep 4 core drivers in main flow; put extended drivers in appendix. |
| Mobile readability | Increase axis label font size; simplify legends. |
| Credibility | Add methods & sources card below first chart. |

---

# Reflection
- My scope grew intentionally: from **Uzbekistan-only** to a **regional narrative**.  
- Prototyping multiple chart forms (indexed lines, small multiples, side-by-side) helped me find the clearest views.  
- User research **re-centered the story**: Kazakhstan matters, migration needs a 5-year baseline, and limits must be explicit.  
- Next week, I’ll refine visuals to show **associations clearly**, prune drivers, and tighten design for **clarity on mobile**.  
- For deeper causal proof, more econometric analysis would be required (panel models, lag tests, instruments), but for Part III I stay at the **visual storytelling level**.

---

## References
- Interview notes (five participants).  
- Housing price data and migration flow statistics (national sources).  

## AI acknowledgements 
AI was used to fix my sentences and streamline my thoughts.

