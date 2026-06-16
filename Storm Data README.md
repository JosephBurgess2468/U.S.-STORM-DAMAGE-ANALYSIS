U.S. STORM DAMAGE ANALYSIS (2015–2024)

PROJECT OVERVIEW

This project focuses on analyzing a decade of storm event data across the United States to identify patterns in financial damage, human impact, and geographic exposure. Using a dataset of 110,141 damage causing storm events sourced from NOAA's National Centers for Environmental Information Storm Events Database, this analysis was built to understand which storm event types, states, and time periods carry the greatest risk to communities and the institutions that serve them. The goal was to demonstrate that historical storm data alone can provide meaningful and actionable insight for insurers, emergency managers, city planners, and financial institutions making risk based decisions.


DATASET

Source: NOAA National Centers for Environmental Information (NCEI) Storm Events Database

Records: 110,141 damage causing events after filtering

Time Period: 2015 through 2024

Files: 10 separate CSV files combined into one master dataset

Features: 13 key variables used across the analysis

Target Variable: Total damage in dollars (property and crop combined)


METHODOLOGY

Damage Parsing: NOAA stores damage values as shorthand strings such as $250K or $1.5M. A custom Python parser was written to convert these into true numeric dollar values for accurate aggregation across all 10 years of data.
Estimating People Affected: Direct casualties capture deaths and injuries but do not reflect the full population impacted by property damage. To estimate broader impact, property damage was divided by the U.S. median home value of $229,800 from the 2020 Census to estimate homes affected, then multiplied by the average household size of 2.53 people. This is an approximation and does not account for renters, commercial property, or infrastructure damage.
Filtering: The dataset was filtered to damage causing events only, meaning events that reported at least some property or crop damage. This removed noise from recorded events with no measurable financial impact and kept the focus on events that directly affected communities.


RESULTS

Total Storm Events Analyzed: 110,141

Total Reported Damage: $260.99 billion

Total Estimated People Impacted: 2,712,308

Worst Single Year: 2017 at $81.45 billion

Most Damaging Event Type: Flash Flood at $80.3 billion (30.8% of all decade damage)

Most Deadly Event Type: Tornado accounting for 17% of all storm fatalities

Highest Damage State: Texas leading total storm losses by a significant margin

Peak Damage Month: August and September accounting for the largest share of annual damage across all 10 years


KEY FINDINGS

1. Flash Flood — $80.3 Billion (30.8% of Total Damage):
The single most damaging event type in the dataset across the entire decade. With 13,628 total events and 577 deaths, flash floods are both the most frequent and most financially destructive category. Damage is spread across nearly every month of the year making them a year round risk unlike any other event type in the dataset. 2017 was by far their worst year driven almost entirely by Hurricane Harvey's unprecedented rainfall totals.

2. Hurricane (Typhoon) — $76.14 Billion (29.2% of Total Damage):
Hurricanes represent the most destructive event type on a per event basis, reaching $76.14 billion in total damage across just 243 events over the decade. To put that in perspective, flash floods required over 13,000 events to reach a comparable damage total. 2022 stands out as the worst hurricane year driven by Hurricane Ian making landfall in Florida. Each individual hurricane carries catastrophic financial exposure that no other event type can match at the same frequency.

3. Wildfire — $29.5 Billion (11.3% of Total Damage):
Wildfires show the most alarming trend in the entire dataset. Damage was relatively contained through 2017 then exploded in 2018 with the Camp Fire in California and has remained elevated every year since. Their death toll of 235 represents 12.8% of all storm fatalities despite being far less frequent than events like flash floods or thunderstorm winds. Wildfires are the clearest evidence of an accelerating risk category in this analysis and represent a growing tail risk that older pricing and risk models may not be fully capturing.

4. Tornado — 17% of All Storm Fatalities:
Tornadoes represent the most significant gap between financial damage and human cost in the entire dataset. While tornadoes account for only about 12% of total financial damage, they are responsible for 17% of all storm fatalities and roughly 43% of all storm related injuries across the decade. That disconnect means communities and institutions focused only on dollar damage are systematically underweighting the human risk tornadoes represent. Early warning systems and shelter infrastructure deserve investment completely independent of financial loss metrics.

5. Seasonal Concentration — August and September:
Across all 10 years of data, August and September consistently account for the largest share of annual storm damage, driven by peak Atlantic hurricane season. This seasonal concentration is one of the most actionable findings in the analysis. Institutions that understand this pattern can use it to time staffing, resource deployment, infrastructure maintenance, and financial hedging ahead of the peak risk window rather than reacting after damage has already occurred.

6. Geographic Concentration — Texas, Florida, and the Gulf Coast:
Texas leads all states in total storm damage by a significant margin, followed by Florida, Louisiana, Puerto Rico, and California. These five states account for a disproportionate share of the nation's total storm losses over the decade. When looking at average damage per event however, smaller states like Hawaii, Puerto Rico, and Louisiana rank highest, meaning they experience individually catastrophic events that are far more severe on a per incident basis. Texas and Florida also lead in annual consistency, confirming that their exposure is not driven by a single outlier year but by persistent recurring risk every year.


REAL WORLD SIGNIFICANCE

The combination of geographic concentration, seasonal predictability, and event type patterns in this dataset means that U.S. storm damage is not random. It follows patterns that are measurable, foreseeable, and actionable. Insurers can use peak season timing to prepare claims capacity. Emergency managers can pre position resources before August arrives. City planners can prioritize flood infrastructure in the highest frequency states. Financial institutions can adjust portfolio risk based on geographic and seasonal exposure.
The 7 false negatives in a clinical model represent missed diagnoses. In storm risk the equivalent is an institution that treats this data as historical record rather than a planning tool — and finds itself unprepared when the next major event hits. The data exists to prevent that outcome. This analysis shows exactly where to look.