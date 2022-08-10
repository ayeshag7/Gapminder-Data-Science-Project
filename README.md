# Gapminder-Data-Science-Project
Ranking countries based on their economic and environmental well-being using Gapminder dataset containing data about many indicators like life expectancy, GDP etc from 1952 to 2012.

## Ranking Name: TESPH
'TESPH' which stands for Technology, Economy and Environment, Social, Population, and Health is a comprehensive rating created from analysing a large proportion of data which shows a country's overall wellbeing over a certain period of time.

Measuring a country's prosperity from just one standpoint would be biased so this ranking was determined in two ways:

Red TESPH:  Measure of a country's economic strength reflected in it's economic growth, diversity, and stability.
  * For RED TESPH, correlation of indicators with Total GDP US was found because GDP is the  most comprehensive measure of economic performance and growth of a country.
    
Green TESPH:  Measure of a country's standard of living in terms of sustainable development and health.
  * For GREEN TESPH, the indicator Life Expectancy was chosen as it determines the overall health status of a country across all ages.
  
## TESPH in Numbers:
Data of 16 Countries from 7 Regions over a time period of 16 Years was distilled into 6 Pillars made up of 25 Indicators.

## Tools Used: 
**Pandas** and **Numpy** Libraries for data analysis. **Matplotlib** and **Plotly Express** Libraries for data visualization.

## Steps Involved / Methodolgy:
* Data Cleaning
* Data Normalization 
* Indicator Selection *Pearson Correlation Coefficient to find the pairwise correlation of all indicators*
* Average Calculation
* Weight Distribution
* Calculation of weighted averages
* Calculation of Aggregate Averages of all pillars *Determining Indicators' Impact based on Correlation,* *Data Anomalies*
* Calculating Final Rankings.

### For further information and key findings please read the Project Report (PDF File) in the code section.
#### Side Note: 
This was my final term project in first semester in college. I'm still learning about Data Science and frankly I've a long way to go. So your suggestions if any to improve this project will be appreciated.
