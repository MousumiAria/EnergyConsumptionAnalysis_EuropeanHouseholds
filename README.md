
<h1> <align="center">Energy Consumption Analysis in European Households</h1>


## Description:

To analyze, visualize, and derive insights from a dataset representing the energy consumption in households across various European countries, segmented by fuel type, over the past decade.

## Analysis for all Countries in European Union  
![EnergyConsumptionAnalysis_EuropeanHouseholds](https://github.com/MousumiAria/EnergyConsumptionAnalysis_EuropeanHouseholds/blob/main/EuropionUnionDataAnalysis.JPG)

## Country wise Data Analysis
![EnergyConsumptionAnalysis_EuropeanHouseholds](https://github.com/MousumiAria/EnergyConsumptionAnalysis_EuropeanHouseholds/blob/main/CountrywiseAnanysis.JPG)

## Dataset details:
A comprehensive dataset detailing the energy consumption across European households, broken down by four major fuel types: Electricity, Natural Gas, Liquid Petroleum Gas and Kerosene. Data spans over a decade, providing a rich temporal context.
It is downloaded from the website: https://ec.europa.eu/eurostat/databrowser/view/TEN00125__custom_7257799/default/table?lang=en

## Columns Description 

1. [geo]:Geopolitical entity(Countries under European consumption)

2. [siec]:Standard International Energy Product Classification(Fuel Type)
a. [G3000]=Natural gas
b. [O4630]= Liquied petroleum gas
c. [O4669]= Kerosene
d. [RA410]=Solar Tharmal
e. [E700]=Electricity

3. [TIME_PERIOD]: In Year

4. [OBS_VALUE]: Unit of Measure(Thousand tonnes of oil equivalent)

## Tools & Technologies:

1. Primary Tool: Power BI

2. Data Modeling: DAX for custom metrics and measures

3. Data Processing: Power Query in Power BI

## Data Preparation:

1. Imported the dataset into Power BI.

2. Conducted data cleaning to address inconsistencies, outliers, and missing values.

## Analytical Operations:
Developed custom measures using DAX to determine consumption proportions and trends for each fuel type.
Established relationships and hierarchies within the data to support multi-dimensional analysis.

i) Total Fuel Consuption

ii) Previous Year Energy Consumption

iii) Current Year Energy Consumption

iv) Year over Year Energy Consumption 

## Visualization & Dashboarding:
Developed an interactive Power BI dashboard.
Incorporated a mix of visualization types, including stacked columns, donut charts, and geographical maps, to represent the data.
Used drill-through, slicers, and custom tooltips to enhance user interactivity and experience.

1. Trends Over Time:

i) Line Chart: Show the yearly consumption of each type of fuel across all countries. This can highlight any significant shifts in fuel preferences over time.

ii) Clustered Column Chart: Compare the yearly consumption of different types of fuel for each country.

2. Country-wise Analysis:

i) Map Visualizations: Display the total energy consumption of each country. Used different colors or sizes to represent amounts of consumption.

ii)Drill-through Functionality: Let users click on a country to see a more detailed breakdown by fuel type.

3. Fuel Consumption Share:

i) Pie/Donut Charts: Show the proportion of each type of fuel consumed in a specific year or averaged over the years.

ii) Stacked Column/Bar Charts: Showcase how much of the total consumption each type of fuel represents for each year or country.

4. Comparative Analysis:

i)Scatter Plots: Compare two countries in terms of their energy consumption patterns to spot outliers or interesting patterns.

ii)Waterfall Chart: If there's a significant change in a country's energy consumption from one year to the next, use this chart to break down the contributing factors (like increase in electricity usage, decrease in gas, etc.).

5. Year-on-Year Growth:

i)Percent Change Calculation: Showcase the YoY growth rate for each type of fuel in each country.

6. Top and Bottom Analysis:

i) Card: To show total energy Consumption

ii) Tables: To show highlight the top 5 countries with the highest consumption for each type of fuel and those with the least consumption.

7. Filters and Slicers:

Allow users to filter the data by country, year, or fuel type to customize their view.


## Key Findings & Insights:

Here's a concise list of potential insights extract from the dataset on energy consumption in households by type of fuel across European countries:-

1. Trends Over Time:

Identification of any significant shifts in fuel preferences over the last 10 years.
Yearly rise or fall patterns in consumption for each fuel type across countries.

2. Country-wise Consumption:

Countries that have consistently had the highest or lowest energy consumption over the years.
Any significant changes in a country's consumption patterns.

3. Fuel Consumption Share:

Proportion of each type of fuel consumed in a specific year or averaged over the decade.
Countries where a particular fuel type dominates the energy consumption landscape.

4. Comparative Analysis:

Countries that have similar or contrasting energy consumption patterns.
Instances where a significant change in one type of fuel's consumption is offset by changes in the consumption of other fuel types.

5. Year-on-Year Growth:

Countries with the most significant growth or reduction in consumption for each type of fuel from one year to the next.

6. Top and Bottom Analysis:

Identification of the top 3 and bottom 3 countries based on their consumption for each type of fuel.

7. Correlations:

Potential correlations between the consumption of two types of fuels, e.g., does an increase in natural gas consumption correlate with a decrease in electricity consumption?

8. Usage Intensity (if population data can be incorporated):

Countries that, despite their size, have high energy consumption per capita.

9. Major Shifts:

Years or periods where there was a noticeable change in energy consumption patterns, possibly pointing to policy changes, economic factors, or technological advancements.

10. Dependency on a Particular Fuel:

Countries that are heavily reliant on a particular type of fuel compared to others.
These insights, derived from the dataset, can provide a comprehensive understanding of energy consumption patterns across Europe, and can further be used to make informed decisions, predict future trends, or influence policy-making.
Identified clear trends in the consumption of different fuel types over the years.
Detected specific countries with shifts in fuel preferences, potentially indicating policy changes, technological advancements, or market shifts.
Highlighted the dominant fuel types for specific countries and discerned any unique consumption patterns.


## Value Proposition:

Provided a visual tool for stakeholders to understand energy consumption patterns in Europe easily.
Enabled data-driven decision-making for policy recommendations, sustainability initiatives, and market strategies.
Supported potential forecasting of future energy trends based on historical data.

## Future Scope & Recommendations:

Incorporate more granular data, such as monthly or weekly consumption metrics, for a detailed analysis.
Extend the dataset to include other relevant metrics like energy prices, household incomes, or carbon emissions to draw more comprehensive insights.
Explore the integration of predictive analytics to forecast future energy consumption trends and advise on sustainability measures.

## Developer: 

<a href="https://github.com/MousumiAria"> Mousumi Sen</a>

## Level: 

Data Analyst

## The timeline of the project: 

August-September 2023**




