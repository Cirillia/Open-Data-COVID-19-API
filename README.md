# COVID-19 Data Analysis Using Open API
## Project Overview
This project involves querying the UK government's open API to fetch COVID-19 data, which includes information about cases, deaths, and vaccinations at national and regional levels. The goal is to perform data transformations and create visualizations to answer specific questions related to the pandemic's impact.

## Notebook Contents
- **Query API**: Functions to fetch data from the Coronavirus data API.
- **Data Wrangling**: Scripts to convert raw JSON data into structured Pandas dataframes.
- **Analysis**: Code blocks dedicated to analyzing the data through various transformations and plotting the results.

## Data Structure
- results_json_national: Data at the national level.
- results_json_regional: Data at the regional level.
- covid_data: Consolidated dataframe for further analysis.
- covid_data_vaccinations: Dataframe focusing on vaccination data.
- Further breakdowns for specific analytical queries.

## Visualization
Several plots are generated to visualize the data:
- Cumulative cases and deaths over time.
- Rolling averages of daily cases and deaths.
- Vaccination uptake by different age groups.
