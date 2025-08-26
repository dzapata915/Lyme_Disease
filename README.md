# Lyme Disease: Case Trends, Climate, and Risk Across the United States
Nashville Software School Capstone Project




## Table of Contents:
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normalizing-the-data)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Data Sources](#data-sources)
* [Conclusion](#conclusion)



## Motivation:
I grew up in New York just 30 miles north of New York City in the suburbs. As a kid, I contracted Lyme disease twice, which we caught early, so I was able to get treated and made a full recovery with no lasting effects. Then I moved down to Nashville in 2012 and remember being told there really was no Lyme disease down here, but I never looked into it. This project allowed me to actually dig into the data and investigate whether that claim was true or not.


## Questions:
1.	How has Lyme disease changed over the past several decades in the United States?

2.	Which states are most affected by Lyme disease and has that changed over time?

3.	Which states have experienced the most significant increase in cases?

4.	Is there a relationship between winter temperatures and case counts?

5.	Does adjusting for population change which states are considered most at risk?

6.	What is the risk of Lyme disease in Tennessee and specifically, Davidson County?


## Normalizing the Data
To ensure consistency and comparability across datasets, I took the following steps:

1. Aligned Time Frames:
    *The county and state level Lyme disease datasets covered different year ranges. I selected a common time frame available in both and removed any years outside that range.

2. Filtered County-Level Data:
    *Rows corresponding to regions were excluded to maintain data at the county level.

3. Cleaned State Names:
    *In the state-level dataset, certain state names included superscripts for footnotes. These were removed to ensure consistent naming across datasets.

4. Reshaped Year Columns:
    *Years were originally listed as column headers. The data was transposed so that years became a single column, enabling easier filtering and analysis by year.

5. Synchronized Date Formats:
    *Dates in the temperature dataset were converted to match the year based time frame used in the case count data.

6. Refined Census Data:
    *Extraneous columns, headers, and footnotes were removed. State and county names were cleaned to align with the CDC’s dataset.

7. Calculated Incidence Rates:
    *Census population data was used to normalize the Lyme disease case counts, allowing for the calculation of incidence rates to display fair comparisons across regions and over time.



## Problems and Hurdles
There were varying time frames available for the Lyme disease data from the CDC depending on the geographical level, so had to choose which windows of time to use in order to adequately analyze the data. Also, the population data from the Census Bureau had a lot of extra headers, footnotes, columns, etc. that needed to be cleaned to make it usable.



## Technologies Used
1) Python / Pandas / Matplotlib / Seaborn- for explorating, normalizing, aggregating, and visualizing of data
2) Power BI - for creating map visualizations
3) PowerPoint - for presentation of project
4) Git - for version control

## Data Sources
To answer the above questions I used the following sources to collect datasets for my analysis:

Centers for Disease Control and Prevention (CDC)- Lyme disease surveillance datasets with varying timeframes
    *https://www.cdc.gov/lyme/data-research/facts-stats/surveillance-data-1.html	

National Centers for Environmental Information (NCEI)- temperature data on the national, regional, and state level
    *https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/

United States Census Bureau- population data on a national, state, and county level
    *https://www.census.gov/data/tables/time-series/demo/popest/2020s-state-total.html	
    *https://www.census.gov/data/datasets/time-series/demo/popest/2020s-counties-total.html


## Conclusion
Cases of Lyme disease have been steadily growing in the United States over the past 30 years. There are certain regions like the Northeast and North-Central that are most inflicted by this disease. States like New York, Pennsylvania, and Wisconsin routinely have a very high number of cases. When we take population into account though, we see that states in New England are actually the most at risk for Lyme. If we narrow our focus down to Tennessee and Davidson County in particular, the risk is almost non-existent with Davidson County only having 3 cases in the last reported year. Over the past 15 years, we have seen states like Ohio and West Virginia start to see a significant increase in their number of cases. The analysis shows that one contributing factor may be rising temperatures during the winter that allow ticks to have a longer active season and more opportunity to contract and spread the Lyme disease bacteria. There are a lot of variables when it comes to Lyme disease, but cases appears to be growing, so it is best to take precautions and always check yourself for ticks!


