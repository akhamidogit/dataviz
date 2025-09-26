| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


> Important note: this includes major elements of Part I.

# Outline
In recent years, Uzbekistan has experienced a dramatic rise in housing prices, particularly in the capital city, Tashkent. Over the last three years, prices have climbed at a rate not seen in the previous decade. This raises an important question: *what exactly is driving this surge?*  

There are multiple explanations. Some point to supply-side issues, such as fewer new houses being built or rising land and property taxes. Others suggest demand-side pressures, including the increasing number of students moving into cities or overall income growth. But one major factor often discussed is the influx of Russian migrants who arrived during the waves of mobilization following the Russia-Ukraine conflict. These sudden inflows of people put additional pressure on Tashkent’s housing market, potentially driving up prices faster than before.  

My project will tell the story of how these factors—migration, supply constraints, and local demand shifts—interacted to shape the current housing market. By combining visualized price trends with contextual data on migration flows and construction activity, I aim to provide a well-rounded picture of why housing has become so expensive in such a short time.  

**Story structure (setup, conflict, resolution)**  
- **Setup:** Uzbekistan’s housing market was relatively stable for nearly a decade, with moderate changes in price.  
- **Conflict:** Starting around 2022, prices spiked dramatically. Competing explanations emerged, including migration shocks from Russia, limited housing construction, and growing local demand.  
- **Resolution:** By visualizing and comparing these factors, the project will highlight how migration shocks amplified existing supply and demand pressures, helping us better understand the dynamics of Tashkent’s housing crisis.  

## Initial sketches
I plan to use sketches to map out the story and the visuals:  

1. **Line chart of housing price growth**  
   - X-axis: Years (2022–2025).  
   - Y-axis: Median monthly housing prices changes (in %), OR Median monthly housing prices (USD or UZS).  
   - Vertical markers for 2022 and 2023, indicating the 1st and 2nd waves of Russian mobilization.  
   - The aim is to clearly show the sudden upward inflection in prices during these years.  

<p align="center">
     <img src="https://github.com/akhamidogit/dataviz/blob/main/Housing%20price%20changes.png" alt="Housing price changes" width="70%" style="margin: 20px 0;">
   </p>


2. **Conceptual diagram of supply and demand factors**  
   - Demand side: Population, household incomes, Russian migration.  
   - Supply side: Housing stock, cost of building materials index.  
   - This sketch will serve as a framework for explaining the competing factors and their relative contributions.  
 
<p align="center">
     <img src="https://github.com/akhamidogit/dataviz/blob/main/Conceptual%20House%20prices.png" alt="Conceptual housing price factors" width="70%" style="margin: 20px 0;">
   </p>

> **Additional note (context on supply and demand factors):**  
   > **Demand Factors**  
   > Interest rates are a major driver of home prices. When interest rates rise, the cost of borrowing increases, which reduces financial options for potential buyers. A 1 percent increase in real interest rates can slow home price growth by about 2 percent. Conversely, low interest rates boost demand by making it easier to get a mortgage.  
   > Population growth raises competition for limited housing stock, driving up prices, especially in urban areas. Migration patterns also amplify this effect – cities like New York, Berlin, and Toronto have experienced substantial price increases due to both domestic and international migration.  
   > Rising incomes generally boost housing demand. Individuals with higher incomes can spend more, which causes prices to rise. GDP growth can boost consumer confidence, encouraging homebuyers to enter the market.  
   >   
   > **Supply Factors**  
   > Higher cost of building materials pushes up overall home prices. The National Association of Home Builders reports that rising costs of materials like lumber, steel, and aluminum significantly affect housing affordability, while global factors such as geopolitical tensions and the demand for sustainable building materials further exacerbate these costs.  
   > Land availability, especially in densely populated urban areas, constrains housing supply, driving prices upward. High population densities and stringent zoning regulations exacerbate this effect, leading to affordability challenges in many global cities.  
   > Stricter land-use regulations, such as zoning laws, directly contribute to higher housing prices by limiting supply. For instance, cities with restrictive land regulations (e.g., San Francisco) exhibit slower housing construction and more rapid price increases following demand hikes. In contrast, less regulated areas like Texas have experienced higher housing elasticity, maintaining lower housing costs over time. Bureaucratic delays in obtaining planning permissions significantly hinder the pace of housing development.  
   >   
   > Although both supply- and demand-side factors shape the housing market, their interaction leads to different real estate cycle phases: recovery, expansion, hyper-supply, and recession. Different phases feature different construction levels, rental and price trends. For instance, during the expansion phase, rental levels increase, and construction begins to catch up with demand.  



These sketches will evolve into polished Tableau/Datawrapper visuals later, but they help lock down my story’s structure and message.  

# The data
**Primary data sources**  
- **Housing prices dataset:** Monthly scraped data from *olx.uz* (Uzbekistan’s main housing listings site). The raw data contains individual listing prices. These have been cleaned and aggregated in R to calculate monthly median housing prices.  
- **Migration data:** Official statistics from *stat.uz* on inflows of foreign nationals, with special focus on Russian migrants since 2022.  
- **Supplementary data:** Construction activity, housing stock, population growth, household incomes, and government land/property taxation policies. These are macroeconomic indicators that allow us to compare demand- and supply-side influences on housing prices.  

**Usage plan**  
- The housing price dataset will form the core visualization, showing trends over the last decade.  
- Migration data will be layered in to test the “Russian inflows” hypothesis by correlating spikes in arrivals with price jumps.  
- Supplementary data will provide context for alternative explanations (population growth, limited housing stock, rising incomes, and taxation).  

| Name | URL | Description |
|------|-----|-------------|
| Housing price dataset | [2022–2024 housing prices](https://github.com/akhamidogit/dataviz/blob/main/2022_2024_housing_prices.xlsx), [2025 August housing price](https://github.com/akhamidogit/dataviz/blob/main/2025_08_housing_price.xlsx) | Monthly scraped OLX listings, cleaned and aggregated into median prices. |
| Migration statistics | (letter to get dataset sent to stat.uz – to be added) | Official data from stat.uz on inflows of foreign nationals (focus on Russians). |
| Supplementary data | stat.uz | Macroeconomic indicators: housing stock (supply fator), population growth (demand factor), household incomes (demand factor). |

# Method and medium
For my final product, I plan to use:  
- **Tableau** for interactive charts (line charts, bar charts, factor breakdowns).  
- **Datawrapper** for clean, static visuals when simplicity is best.  
- **Shorthand** to bring everything together into a narrative story with scrolling text, images, and embedded charts.  

This combination will allow me to not only present the data but also weave a clear and engaging story about housing prices in Uzbekistan—what caused them to surge, and why this matters for policymakers, students, and the public.  

## References
- Official statistics portal of Uzbekistan: [stat.uz](https://stat.uz)  
- OLX Uzbekistan housing listings: [olx.uz](https://www.olx.uz)  

## AI acknowledgements
I used AI (ChatGPT) to help fix grammar the initial structure and wording of my Part I proposal, including organizing sections, polishing language, and aligning the content with the GitHub template. The ideas, topic selection, and data sources are my own.  

