# Exploring-Global-Metrics-Insights-into-International-Policymaking

## Project Overview
This repository contains a comprehensive analysis of global metrics in international policymaking, utilizing the world-data2023.csv dataset. The exploration delves into the intricate relationships between various economic, demographic, and sociocultural indicators, revealing the stories behind the numbers that shape our understanding of global dynamics.

Dataset Description
The world-data2023.csv dataset encompasses a variety of global metrics, with Country as a unique identifier for observations. Key variables include:
- Economic Indicators:
   - GDP (Gross Domestic Product)
   - Minimum Wage
   - Out-of-Pocket Health Expenditure
   - Armed Forces
   - Consumer Price Index (CPI) and CPI Change
   - Tax Rate
     
- Demographic Statistics:
   - Population
   - Population Density
   - Life Expectancy
     
- Human Development Index:
   - Infant Mortality
   - Birth and Fertility Rate
   - Gross Primary and Tertiary Education Enrollment
   - 
- Sociocultural Metrics:
   - Official Language
     
- Environmental Factors:
   - CO2 Emissions
   - 
The primary focus of this analysis is on GDP, population density, life expectancy, and minimum wage as they significantly influence immigration policies and decision-making in international contexts.

## Data Cleaning Process

Data cleaning was conducted using Excel's Power Query Editor. Key steps included:
 1. Removing Non-Key Variables: Non-influential variables related to immigration were eliminated.
 2. Deduplication: Duplicate entries were identified and removed using conditional formatting.
 3. Handling Missing Values: A Listwise deletion approach was employed to omit cases with missing data while ensuring unbiased estimates.
 4. 
Despite these efforts, potential issues such as incompleteness and inaccuracies remain a concern, particularly regarding healthcare metrics that can mislead policy decisions.

## Key Insights

### Life Expectancy Analysis

- Regional Variations: Sub-Saharan Africa exhibits a lower average life expectancy (62.44 years) compared to North America (80.2 years), highlighting the need for targeted healthcare interventions.
- Correlation with Minimum Wage: A scatter graph indicates a positive correlation between minimum wage and life expectancy, with an R-squared value of 0.4099 suggesting that while there is a relationship, other factors also play significant roles.
- 
### Economic Indicators

GDP Trends: North America leads with an average GDP of approximately $10.71 trillion, followed closely by Asia Pacific ($1.06 trillion) and Europe ($460 billion). This data can guide policymakers in addressing regional economic disparities.

### Birth Rate and Education Correlation

A negative correlation between birth rates and gross tertiary education enrollment suggests that higher education levels may contribute to lower birth rates, particularly in regions like North America and Europe.

### Environmental Considerations
The analysis of land use indicates that regions like Asia Pacific balance agricultural land with forested areas effectively, while Sub-Saharan Africa's high agricultural land percentage poses challenges for sustainable resource management.

## Conclusion
This project underscores the importance of data-driven insights in shaping international policies. By analyzing key metrics such as GDP, life expectancy, and population density, we can better understand the complex interplay between economic conditions and societal well-being. The findings advocate for targeted policy interventions aimed at enhancing quality of life globally while addressing the challenges posed by demographic changes.

## Future Work
Further research is needed to explore unaccounted factors influencing life expectancy and other metrics. Continuous monitoring of these indicators will be vital for informed policymaking in an increasingly interconnected world.
