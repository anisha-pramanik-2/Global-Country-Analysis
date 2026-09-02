# Global Country Analysis Using Python

## Overview

This project analyzes a global country dataset using Python to explore demographic, geographic, environmental, and defense-related indicators. The analysis focuses on data cleaning, statistical analysis, filtering, grouping, correlation analysis, and data visualization.

## Dataset

The dataset contains information for **195 countries** and includes:

- Country
- Abbreviation
- Agricultural Land (%)
- Land Area (Km²)
- Armed Forces Size
- Birth Rate
- Calling Code
- Capital/Major City
- CO₂ Emissions

Dataset source: [Countries of the World 2023 - Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/countries-of-the-world-2023)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Data Cleaning

The dataset was cleaned by:

- Removing the completely empty `Density(P/Km2)` column
- Converting numeric columns to appropriate numeric data types
- Removing commas and percentage symbols from numeric values
- Handling missing numeric values using median imputation
- Handling missing text values using the mode
- Fixing corrupted character encoding in country and capital names
- Checking the final dataset structure

## Analysis Performed

- Top 10 countries by land area
- Top 10 countries by CO₂ emissions
- Top 10 countries by birth rate
- Top 10 countries by armed forces size
- Top 10 countries by agricultural land percentage
- Correlation analysis between numerical indicators
- Land area vs. CO₂ emissions
- Armed forces size vs. CO₂ emissions
- Birth rate distribution
- CO₂ emissions distribution
- Agricultural land group analysis
- Birth rate group analysis
- Summary statistics
- Percentile analysis
- Conditional filtering and country-level comparisons

## Statistical Analysis

NumPy was used for mean, median, minimum, maximum, and percentile calculations.

Pandas was used for grouping and aggregation, filtering, value counts, summary statistics, conditional analysis, and `idxmax()` analysis.

## Key Insights

- Average birth rate: **20.15**
- Median birth rate: **17.95**
- Average agricultural land: **39.13%**
- Median land area: **119,511 Km²**
- The high agricultural-land group had the highest average birth rate among the three agricultural-land groups.
- **Russia** has the largest land area in the dataset.
- **India** has the largest recorded armed forces size.
- **Niger** has the highest birth rate.
- **Uruguay** has the highest agricultural land percentage.
- Five countries have an armed-forces value recorded as zero.

## Visualizations

The project includes Matplotlib visualizations such as:

- Bar charts
- Horizontal bar charts
- Scatter plots
- Histograms
- Boxplots
- Correlation heatmaps

A consistent charcoal and blue theme was used across the visualizations.

## Project Structure

```text
Global-Country-Analysis/
│
├── data/
│   └── global_country_analysis_cleaned.csv
│
├── notebook/
│   └── Jupyter Notebook
│
└── README.md