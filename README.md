# Energy-Consumption-Analysis-using-MySQL
# 

##  Overview

Analyzed global energy consumption, production, emissions, GDP, and population data using **MySQL** to explore relationships between economic growth, energy usage, and environmental impact.

##  Tools Used

* MySQL
* SQL
* CSV datasets

##  Objectives

* Identify countries with the highest GDP and emissions.
* Compare energy production and consumption.
* Analyze global emissions trends over time.
* Calculate per-capita energy consumption and emissions.
* Examine emissions relative to GDP.
* Investigate relationships between GDP growth and energy production.

##  Database Schema

The database contains six tables:

| Table         | Description                            |
| ------------- | -------------------------------------- |
| `country`     | Country reference data                 |
| `consumption` | Energy consumption by country and year |
| `production`  | Energy production by country and year  |
| `emission_3`  | Emissions and per-capita emissions     |
| `gdp_3`       | GDP data by country and year           |
| `population`  | Population data by country and year    |

##  SQL Concepts

* Joins and aggregations
* `GROUP BY` and `HAVING`
* Subqueries and CTEs
* Window functions (`LAG`, `RANK`)
* Year-over-year growth calculations
* Per-capita metrics and ratios
* Conditional logic using `CASE WHEN`



##  Key Analysis

* Country-level emissions and GDP rankings
* Energy production vs. consumption
* Global emissions trends
* Emissions per capita
* Energy consumption per capita
* Emissions-to-GDP ratios
* Country comparisons over time


##  Project Structure

```text
global-energy-analysis/
├── data/
├── MySQL/
├── presentation/
└── README.md
```

##  Data Source

* [U.S. Energy Information Administration (EIA)](https://www.eia.gov/)

