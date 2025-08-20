# Lyme_Disease
NSS Capstone Project- Lyme Disease in the US




# Human Migration




## Table of Contents
* [Tableau Dashboard](#Tableau-dashboard)
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normaling-the-data)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Data Sources](#sources)
* [Conclusion](#conclusion)

## Tableau Dashboard
Link: https://public.tableau.com/views/HumanMigration_16511842170780/Story2?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

## Motivation:
Being an immigrant myself and having seen the trouble my family faced to migrate from my homeland for better life, I wanted to take this opportunity to do some research and find which countries most of the migrants are coming from and which countries they are going to. I decided to narrow down top 10 countries of origin and destination and research push and pull factors of migration.
Push factors include:
- Violence
- Poverty
- Lack of safety
- Unemployment

Pull factors include:
- Higher Employment
- Wealth
- Safety
- Climate

## Questions:
1) Which countries do people migrate from the most?
2) Which countries are people migrating to the most?
3) What are the push and pull factors?
4) Is there a correlation between factors such as unemployment rate, violence, infant mortality rate, religious freedom and migrants?

## Normalizing the Data
The dataset I selected mainly consisted of years from 1970 through 2019. I selected the most recent given data - 2019. I then created multiple dataframes and narrowed down to the values that I wanted to use for my analysis. My initial approach was to use data from 2 years 2015 and 2019 and then compare the difference/ correlation, after having done the entire process in Python I realized that there was not much of a difference between the two and therefore I ended up using 2019 data.

## Problems and Hurdles
It was a challenge to clean and organize data in Python for some of the dataset. Statistical Risk Assessment data consisted of values in log format and that required some calculation in python to convert it to readable value. Web- scarping Global Peace Index was another hurdle that took some time to work.

## Technologies Used
1) Python / Pandas - for exploration, normalizing and aggregation of the dataset
2) Tableau - for creating interactive dashboard
3) PowerPoint - for introduction of Project
4) Git - for version control

## Data Sources
To answer the above questions I used the following sources to collect datasets for my analysis

1) International Migration data from United Nations Department of Economics and Social Affairs- Population Division.
https://www.un.org/en/development/desa/population/migration/data/estimates2/estimates19.asp

2) Early Warning Projects by ushmm.org. The dataset includes 2021-22 Statistical Risk Assessment for Mass Killing by Country.
https://earlywarningproject.ushmm.org/ranking-of-all-countries

3) Wikipedia (web-scrapped the Global Peace Index)
https://en.wikipedia.org/wiki/Global_Peace_Index

4) OECD.Stat (Organization for economic co-operation and development)
https://data.oecd.org/unemp/unemployment-rate.htm

## Conclusion
The data analysis shows countries with most incoming immigrants are USA, UK, Saudi Arabia, Russia, Germany, Australia, France, Italy and Canada. It is given that theses countries have better opportunities for work, health and education that can drive people to move for better life for themselves and their loved ones. Countries where people are moving from include Mexico, India, Syria, Ukraine, China, Russia, Pakistan, Philippines, Afghanistan. My analysis shows some of these countries are ranked high in statistical risk assessment for mass killing however the correlation was not sufficient enough to claim that this could be the cause of migration. Most of the countries are developing countries and it could be concluded that violence, religious freedom, and unemployment could also play a vital role in migration.