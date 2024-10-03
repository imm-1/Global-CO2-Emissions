# Global CO2 Emissions Dashboard

## Project Overview

This project presents an interactive Tableau dashboard that visualizes 250 years of global CO2 emissions data. The dashboard provides insights into the historical trends, geographical distribution, and relationship between CO2 emissions and population across countries.

## Objectives

1. **Profile & QA the Data**: Clean and optimize the data for visualization.
2. **Visualize the Data**: Create visualizations to show CO2 emissions trends, geographical distribution, and relationships with population.
3. **Build an Interactive Dashboard**: Combine visualizations into a user-friendly dashboard with interactive filters and parameters.

## Data Source

The dataset used in this project is `visualizing_global_co2_data.csv`. It contains historical CO2 emissions data at the country level.

## Key Steps

### Objective 1: Profile & QA the Data
- **Data Source Filter**: Excluded records with NULL `Iso Code`.
- **Field Types**: Converted fields with “Co2” in their names to Number (Whole) and set them as continuous measures.
- **Parameter Creation**: Created a `Top N` parameter with a default value of 10.

### Objective 2: Visualize the Data
- **Line Chart**: Showed the % of total share of CO2 by year for the top 10 countries.
- **Map**: Displayed CO2 per capita at the country level for the year 2021.
- **Scatter Plot**: Compared CO2 emissions and population, with bubble size representing temperature change from CO2 for the year 2021. Added a linear regression trend line.
- **Color Scale**: Applied a divergent color scale based on CO2 per capita.

### Objective 3: Build an Interactive Dashboard
- **Dashboard Layout**: Assembled the line chart, map, and scatter plot into a dashboard.
- **Interactive Filters**: Added a country filter and a `Top N` parameter for user interaction.
- **Polishing**: Adjusted formatting and alignment for a polished final presentation.

## Insights and Observations

- **Top Contributors**: Identified countries like China, the USA, and India as the largest contributors to CO2 emissions.
- **Per Capita Emissions**: Highlighted countries with high per capita emissions.
- **Trends**: Analyzed trends in CO2 emissions over time and observed significant shifts and anomalies.

## Usage

1. **Open the Tableau Dashboard**: Load the Tableau workbook file to view the interactive dashboard.
2. **Explore the Visualizations**: Use the filters and parameters to interact with the data and uncover insights.
3. **Analyze Patterns**: Observe trends and patterns in global CO2 emissions data.

## Conclusion

The Global CO2 Emissions Dashboard provides a comprehensive view of historical CO2 emissions data, enabling users to explore and understand the impact of various countries on global emissions over time. This tool serves as a valuable resource for researchers, policymakers, and anyone interested in environmental data analysis.
