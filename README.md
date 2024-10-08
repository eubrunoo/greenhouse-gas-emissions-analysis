﻿# Greenhouse Gas Emissions Analysis

This repository contains an analysis of greenhouse gas emissions across all Brazilian states. The goal of this project is to compute the per capita emissions by combining data on total emissions and population.

## Project Overview

In this project, I utilized two datasets:
1. **Greenhouse Gas Emissions Dataset**: This dataset provides the total greenhouse gas emissions for each state in Brazil.
2. **Population Dataset**: This dataset includes the population of each state in Brazil.

### Steps Performed

1. **Data Loading**: Both datasets were loaded into the environment using the Pandas library.
2. **Data Cleaning and Preparation**: 
    - The datasets were cleaned to remove any inconsistencies.
    - Necessary transformations were applied to ensure that the data could be accurately merged.
3. **Data Integration**: 
    - The emissions dataset was merged with the population dataset based on the state names.
    - Calculations were performed to derive the per capita emissions for each state.
4. **Exploratory Data Analysis (EDA)**: 
    - Initial exploration of the data was conducted to understand the distribution and patterns in greenhouse gas emissions and population across states.
5. **Results and Visualization** (Upcoming):
    - Graphs and visualizations will be generated to present the findings in a clear and concise manner.

### Next Steps

- Add visualizations to summarize and present the results.
- Finalize the analysis with conclusions drawn from the data.

### Acknowledgments

- The greenhouse gas emissions data was sourced from [SEEG](https://seeg.eco.br/).
- The population data was obtained from [IBGE](https://www.ibge.gov.br/).

## Libraries Used

- **Pandas**: For data loading, cleaning, manipulation, and merging.

## How to Run

To run this analysis, clone this repository and execute the `main.ipynb` notebook. Ensure that you have the required datasets and the necessary Python libraries installed.

```bash
git clone https://github.com/eubrunoo/greenhouse-gas-emissions-analysis.git
cd greenhouse-gas-emissions-analysis
jupyter notebook main.ipynb
