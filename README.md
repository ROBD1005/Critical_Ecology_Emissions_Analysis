# Critical Ecology Emissions Analysis

Repository for analyzing the relationship between the racial wealth gap and industrial emissions outputs in the United States. By leveraging data from the EPA’s NEI and US Census labor force statistics, the project aims to explore how socio-economic disparities, particularly the racial wealth gap, correlate with air pollution emissions.


# Quantifying the Racial Wealth Gap & Industrial Emissions Outputs

## Overview

This repository contains scripts, data, and documentation for analyzing the intersection of racial wealth disparities and industrial emissions outputs in the United States. By utilizing datasets from the Environmental Protection Agency (EPA) National Emissions Inventory (NEI), IPUMS Current Population Survey (CPS), and IPUMS National Historical Geographic Information System (NHGIS), this project aims to identify and quantify correlations between socio-economic inequalities and ecological change across different demographic groups and geographic locations.
Critical Ecology integrates a socio-political perspective into environmental science, emphasizing the need to understand the socio-economic origins of environmental degradation, particularly in relation to race, class, and gender. This project applies a critical ecological approach to explore how the racial wealth gap contributes to disproportionate exposure to pollution and environmental harm, and how industrial emissions correlate with socio-economic status and demographic factors.

## Objectives

- **Analyze industrial emissions**: Leverage EPA NEI data to evaluate annual emissions outputs from various industrial sources, focusing on pollutants such as sulfur dioxide (SO₂), nitrogen oxides (NOₓ), and greenhouse gases.
- - **Quantify the racial wealth gap**: Use data from the IPUMS CPS and NHGIS to analyze income disparities, wealth accumulation, and socio-economic status among different racial groups.
- **Integrate Critical Ecology**: Examine how socio-political factors, including racial and economic inequalities, intersect with environmental issues, particularly industrial emissions and pollution.
- **Correlate wealth and emissions data**: Integrate racial wealth data with emissions output to identify potential patterns, trends, and correlations that highlight environmental injustices and socio-economic impacts of industrial activities.

## Data Sources

- **EPA National Emissions Inventory (NEI):** Annual datasets on emissions from point, non-point, on-road, and non-road sources across the United States.
- **IPUMS CPS (Current Population Survey):** Microdata on labor force participation, income, and demographic variables.
- **IPUMS NHGIS (National Historical Geographic Information System):** Data on demographic, socio-economic, and environmental factors at various geographic levels.
- **Labor Force Statistics:** Additional data on employment, wages, and economic activity by race and region.
- **Critical Ecology Data:** Insights on the socio-economic origins of industrial emissions and their biogeochemical impacts on ecosystems, particularly in forest regions.

## Structure of the Repository

- **`data/`**: Contains raw and processed data files, including:
  - `NEI_Annual_Emissions.csv`
  - `IPUMS_CPS_Data.csv`
  - `IPUMS_NHGIS_Data.csv`
  - `GHGRP_data_parent_company_09_2023.xlsb`
  - `GHGRP_oris_power_plant_crosswalk.csv`
  - `Critical_Ecology_Data.csv`

- **`scripts/`**: Contains data processing, analysis, and visualization scripts, including:
  - `data_cleaning.R`: Scripts for cleaning and formatting the raw data.
  - `emissions_analysis.py`: Python script for analyzing annual emissions data.
  - `wealth_gap_analysis.R`: R script for analyzing racial wealth disparities using IPUMS data.
  - `critical_ecology_integration.py`: Python script to integrate Critical Ecology perspectives into the analysis.

- **`visualizations/`**: Contains plots and charts generated from the analysis, such as:
  - Gini coefficient maps
  - Emissions output comparisons by state and year
  - Correlation matrices
  - Visual representations of Critical Ecology data

- **`results/`**: Contains the results of the analysis, including summary statistics, regression models, and findings, with a focus on socio-political contexts.

## Funding



## Acknowledgments

- EPA for providing access to the National Emissions Inventory data.
- IPUMS CPS and IPUMS NHGIS for providing demographic and socio-economic data.
- Critical Ecology for providing a framework to understand the intersection of socio-political factors and environmental science.
- All contributors to the development and maintenance of this repository.

---

**Contact Information:**
For questions or collaboration opportunities, please contact. 
