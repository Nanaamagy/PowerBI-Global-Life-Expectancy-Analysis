# PowerBI-Global-Life-Expectancy-Analysis
## Table Of Content

[Project Overview](#ProjectOverview)

[Objectives](#Objectives)

[Data Source](#DataSource)

[Tools Used](#ToolsUsed)

[Skills_Demonstrated](#Skills_Demonstrated)

[Insights](#Insights)

[Recommendations](#Recommendations)

## Project Overview

A Power BI exploration of global health and socio-economic indicators (2000–2015) to understand how mortality, immunization, and economic context relate to life expectancy across countries.

## Data Source

Data was sourced from Kaggle

## Tools

Power BI (data modeling, DAX measures, interactive visuals).

## Data Processing

Imported and profiled multiple indicator tables; standardized country/status fields.

Cleaned missing/erroneous values and normalized units (K, M, %).

Built a star-schema model with Calendar & Country dimensions for time/status slicing.

Created DAX measures (e.g., Total Adult Mortality, Avg. Life Expectancy, % by Status).

Added slicers (Country, Year/Status) and tooltips; applied consistent typography and color.

## Skills Demonstrated

Data transformation • Data processing • Data analysis • Visualization • Critical thinking • Problem-solving.

## Objectives

Track life expectancy trends over time.

Compare mortality burden (infant & under-5) across high-impact countries.

Examine immunization distributions.

Connect socio-economic context (GDP, expenditure, income composition) to health outcomes.

## Data Analysis & Visualization

<img width="2637" height="1487" alt="Life Expectancy" src="https://github.com/user-attachments/assets/3310be0c-97cf-4470-845d-8bce262edd0a" />
<img width="2627" height="1490" alt="Health Outcome" src="https://github.com/user-attachments/assets/729810ff-1f59-490c-939d-b19b11d79c4d" />
<img width="2620" height="1522" alt="Socio-economic" src="https://github.com/user-attachments/assets/a8a3d15b-208f-4e60-83cb-54998ca95f09" />

Global Life Expectancy: After an early-2000s dip, average life expectancy rises steadily to 71.4 years by 2015.

Mortality & Burden:

Infant deaths (Top 6): India (~14.0K), Nigeria (5.2K), China (4.6K), Pakistan (4.4K), Indonesia (2.3K), Bangladesh (1.7K).

Under-5 mortality (Top 6): India (~18.5K) and Nigeria (~8.3K) remain highest.

Adult mortality peaks in the late 2000s, then trends downward into the 2010s.

Immunization Mix: Polio accounts for the largest share (~83.6%) of recorded immunization cases; HepB (~8.6%) and Measles (~7.9%) are smaller shares.

Country Status: Majority of observations are from developing contexts (~85.8%).

Top Life Expectancy (sample): Ireland (83.44), Canada (82.23), France (82.21), Italy (82.15), Spain (82.02).

Socio-Economic Context:

Global GDP generally climbs through 2012 before softening.

Highest reported total health expenditure appears in Afghanistan ($132.0), Maldives ($123.6), Bhutan ($80.2), Nepal ($72.0), India (~$47.9).

Income composition skews toward developing contexts (~58.4%) vs. developed (~41.6%).

## Insights

Progress with gaps: Life expectancy improved overall, but the burden of infant/under-5 mortality is concentrated in a handful of populous countries.

Immunization focus: Polio dominates reported immunization activity, aligning with eradication efforts; measles and HepB remain non-trivial shares.

Context matters: Countries classed as developing represent most observations and typically face higher mortality alongside tighter resource envelopes.

Economic linkage: Periods of rising GDP coincide with gradual gains in life expectancy, suggesting macro-economic tailwinds for health—though not uniformly.

## Recommendations

Target hotspots: Prioritize high-burden countries (e.g., India, Nigeria, Pakistan) with integrated maternal/child health interventions.

Broaden immunization balance: Sustain polio momentum while strengthening measles and HepB coverage to reduce under-5 mortality further.

Invest in primary care & data systems: Channel expenditure toward community health, surveillance, and timely data to sharpen local decisions.

Socio-economic levers: Pair health programs with poverty reduction, WASH, and education initiatives to compound life-expectancy gains.

Equity monitoring: Track outcomes by status (developed vs. developing) to close persistent mortality gaps.
