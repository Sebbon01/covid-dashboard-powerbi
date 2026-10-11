# COVID-19 Data Analysis

This project uses Oracle SQL and Power BI to analyze COVID-19 data from 01.2020 to 07.2020, across countries, continents, and WHO regions.

## Project Overview

Oracle SQL views prepare the data for analysis, while the Power BI report presents the results and trends.

The analysis includes:
- Confirmed cases, deaths, recoveries, and active cases
- Cases and deaths per million people
- Fatality and recovery rates
- Weekly case growth by country
- Global daily trends and 7-day averages of new cases and deaths
- Testing statistics
- Comparisons across continents and WHO regions

## Technologies

- **Oracle SQL** — data preparation and analytical views
- **Microsoft Power BI** — data visualization and reporting

## Files

- `COVID.pbix` — Power BI report
- `WIDOKI ORACLE.txt` — Oracle SQL view definitions

## Oracle Views

The SQL file defines views for:
- `CONTINENTCOMPARISON` — comparison of COVID-19 statistics by continent
- `COUNTRYRANKING` — country-level statistics and rates
- `FASTESTGROWING` — countries with positive weekly growth and more than 1,000 confirmed cases
- `FATALITYRANKING` — fatality and recovery rates for countries with at least 5,000 confirmed cases
- `GLOBALTREND` — global daily statistics and 7-day averages
- `TESTINGEFFICIENCY` — testing statistics by country
- `VW_TOPCOUNTRIES_DAILY` — daily statistics for selected countries
- `WHOREGIONS` — aggregated statistics by WHO region

## How to Use

1. Open `COVID.pbix` in Power BI Desktop or open the link
