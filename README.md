# COVID-19 Explorary Data Analysis - Human vs Disease 

## Summary
- Conducted data cleaning and data wrangling process of four datasets with over 200,000 entries and 30 variables with Pandas. Addressed missing values and dealt with inconsistent data entries. Converted the datasets to summarized data frames that contain the total and daily information by calculating useful metrics and aggregated values.
- Data Visualization with Plotly: Displayed the growing trends of key metrics related to disease and vaccination progress to directly show human’s race against Covid. Showed case distribution through geographic scatter plot with the day-by-day increasement through animation. Explored the possible relationships between the key variables.
- Data Analysis: Analysed the data along with the corresponding visualizations, provide insights that can get from the data and summary of important information.  

## Dataset

Source: https://www.kaggle.com/josephassaker/covid19-global-dataset, https://www.kaggle.com/gpreda/covid-world-vaccination-progress

## Target  
Perform an EDA on the datasets, and provide some insights that can get from the data and corresponding visualization results.  

## Conclusion
**Countries**
- Top 20 confirm rate countries are: Andorra, Montenegro, Gibraltar, Seychelles, San Marino, Georgia, Czech Republic, Slovenia, Aruba, UK, Lithuania, Saint Barthelemy, Netherlands, Belgium, Estonia, Croatia, Ireland, USA, Maldives, Channel Islands. **Generally, the death rate is high in the high confirm rate countries.   **
- Top 20 death rate countries are: Yemen, Vanuatu, Western Sahara, Peru, Mexico, Sudan, Eduador, Syria, Egypt, Somalia, Taiwan, Afghanistan, Bosnia And Herzegovina, China, Liberia, Bulgaria, Niger, Myanmar, Paraguay, Macedonia. The percentage of vaccinated varies - some of them have over an over 80% vaccination rate. **But for most of the high death rate countries, the overall vaccination rate is low. ** 
**Possible strategies**
- Percentage of vaccination vs. test rate: There seems to exist a positive relationship: if the vaccination rate is higher, the test rate tends to be higher as well. **This means if a country has a more positive and cautious attitude towards the epidemic, both the vaccination rate and the test rate will get higher.**
- Test rate vs. critical rate: There seems to exist a negative relationship: if the test rate is higher, the critical rate tends to be lower. There's also a few extreme cases with very high test rate and a critical rate nears 0, and a few cases with a test rate that is close to 0 and a very high critical rate. **This means if a country test very often, it can decrease the probability that cases become severe and critical.**
- Fully vaccination rate vs. death rate: Although it's not that obvious due to the variation in death rate, there seems to exist a negative relationship: if the fully vaccination rate is higher, the death rate tends to be lower. **This means fully vaccination may decrease the probablity of death caused by the virus.**
**Trends**
- There exists periodic fluctuation in daily new cases and active cases over time: It will go up for about 3 months, and then go down for about 3 months. 
- There's a huge rapid growth in new cases and active cases in the end of 2021 and January 2022. Possible reasons would be more frequent travelling due to the holidays, and the high infectivity of Omicron. However, the number of vaccination goes down in this period.
**Vaccination**
- The two most popular vaccination combinations which has a significant advantage are: *Johnson&Johnson, Moderna, Oxford/AstraZeneca, Pfizer/BioNTech*, and *Oxford/AstraZeneca*. Both of them are used by more than 20 countries. 
- Pfizer has absolute dominance in vaccination, followed by Moderna.  
- The number of fully vaccinated people is many times of the number of cases. With the rapid growing trend of number of vaccinations, I'm confident that we human can beat the disease!