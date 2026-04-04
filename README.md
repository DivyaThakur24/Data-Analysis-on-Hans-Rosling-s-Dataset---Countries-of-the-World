# Data Analysis on Hans Rosling's Dataset - Countries of the World

[![Python](https://img.shields.io/badge/Python-EDA-blue?style=flat&logo=python)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)](https://jupyter.org/)
[![Dataset](https://img.shields.io/badge/Countries-227-success)](#dataset)
[![Columns](https://img.shields.io/badge/Columns-20-teal)](#dataset)
[![License](https://img.shields.io/badge/License-MIT-lightgrey)](./LICENSE)

![CoverPic](https://user-images.githubusercontent.com/36337727/179342592-941a0dd2-6cee-4d8d-ade9-0eb3ddb9cffc.png)

Exploratory data analysis and visualization project based on a countries-of-the-world dataset containing population, GDP, literacy, mortality, land use, climate, and economic sector indicators.

## Table Of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Goals](#project-goals)
- [Tools Used](#tools-used)
- [Data Cleaning Performed](#data-cleaning-performed)
- [Analysis Workflow](#analysis-workflow)
- [Questions Explored](#questions-explored)
- [Key Insights At A Glance](#key-insights-at-a-glance)
- [Key Learning Themes](#key-learning-themes)
- [Correlation Analysis](#correlation-analysis)
- [Files In This Repository](#files-in-this-repository)
- [How To Use](#how-to-use)
- [What This Project Demonstrates](#what-this-project-demonstrates)
- [Future Improvements](#future-improvements)
- [Author](#author)

## Overview

This project explores country-level demographic and socioeconomic indicators inspired by the kind of global development storytelling associated with Hans Rosling.

The notebook focuses on:

- cleaning real-world tabular data
- converting inconsistent numeric formats
- handling missing values
- exploring distributions and outliers
- comparing countries and regions through visual analysis
- understanding relationships between population, literacy, GDP, climate, and land use

The project is built as a hands-on EDA exercise using Python and Jupyter Notebook.

## Dataset

The dataset is stored in:

- `countries_of_the_world.csv`

### Dataset Snapshot

- Rows: `227`
- Columns: `20`

### Example Columns

- `country`
- `region`
- `population`
- `area_sq_mi`
- `pop_density_per_sq_mi`
- `coastline_coastarea_ratio`
- `net_migration`
- `infant_mortality_per_1000_births`
- `gdp_$_per_capita`
- `literacy`
- `phones_per_1000`
- `arable`
- `crops`
- `other`
- `climate`
- `birthrate`
- `deathrate`
- `agriculture`
- `industry`
- `service`

## Project Goals

- inspect the dataset structure and datatypes
- clean messy numeric fields
- handle missing values
- remove unnecessary columns
- analyze distribution and outliers using boxplots and histograms
- answer region-based and climate-based business questions
- study feature relationships using a correlation heatmap

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning Performed

The notebook includes practical data preparation steps such as:

- replacing commas with decimal points in numeric-looking columns
- converting object columns into numeric float types
- filling missing values
- checking for duplicate rows
- dropping the `other` column

This is a useful example of how real-world data often needs cleaning before analysis can begin.

## Analysis Workflow

### 1. Data Manipulation

- understand the structure of the dataset
- inspect columns and data types
- prepare the data for analysis

### 2. Data Cleaning

- fix formatting issues in numeric columns
- convert values to usable numeric types
- impute missing values
- identify and remove unnecessary data

### 3. Data Visualization

The notebook uses:

- histograms for univariate distribution analysis
- boxplots for outlier and spread analysis
- barplots for region-based comparison
- line plots for trend-style comparisons
- heatmaps for correlation analysis

## Questions Explored

The notebook explicitly explores questions such as:

### Q1. How much land is arable in each climate?

This compares land use patterns across climate categories.

### Q2. Which region has the highest literacy?

This investigates literacy differences across world regions.

### Q3. Which region has the highest GDP?

This compares economic strength by region.

### Q4. Which region has the highest population?

This examines regional population concentration.

## Key Insights At A Glance

| Area | Insight |
|---|---|
| Data Quality | Numeric values required cleaning because several columns used commas instead of decimal points |
| Missing Values | Some columns needed imputation before analysis could continue |
| Regional Comparison | The notebook compares literacy, GDP, and population at the region level |
| Climate Analysis | Arable land is analyzed across climate categories |
| Visualization | Histograms, boxplots, barplots, line plots, and heatmaps are used to tell the story |
| Correlation | The heatmap helps identify which country indicators move together and which do not |

## Why This Project Matters

This project is a strong example of how exploratory data analysis can be used to move from raw global data to meaningful questions about development, geography, and socioeconomic patterns.

It is especially valuable because it combines:

- practical data cleaning
- statistical thinking
- visual comparison across categories
- correlation-driven exploration
- region and climate level reasoning

## Key Learning Themes

This project is especially useful for understanding:

- how to clean mixed-format datasets
- how to compare regions using grouped visualizations
- how to spot outliers with boxplots
- how to interpret relationships between country-level development indicators
- how to move from raw data to meaningful exploratory questions

## Correlation Analysis

The notebook also includes a heatmap to explore relationships between numerical variables.

This helps identify:

- positive correlations
- negative correlations
- variables that may move together
- indicators that are weakly related or largely independent

## Files In This Repository

```text
.
|-- countries_of_the_world.csv
|-- LICENSE
|-- README.md
`-- Starter Notebook.ipynb
```

## How To Use

### Open The Notebook

Open:

- `Starter Notebook.ipynb`

Run the notebook cell by cell to reproduce the data cleaning and analysis steps.

### Install Dependencies

If needed, install the common analysis libraries:

```bash
pip install pandas numpy matplotlib seaborn notebook
```

Then launch Jupyter:

```bash
jupyter notebook
```

## What This Project Demonstrates

This project demonstrates:

- exploratory data analysis on global development data
- practical data cleaning
- handling inconsistent numeric formatting
- grouped comparison across regions and climates
- visual storytelling with statistical plots
- correlation-based feature analysis

## Future Improvements

- add a short summary of findings directly in the notebook output
- create cleaner visual exports for the README
- build interactive charts using Plotly
- compare GDP, literacy, and mortality together in a dashboard
- create a country clustering analysis using unsupervised learning

## Author

**Divya Thakur**

- GitHub: [DivyaThakur24](https://github.com/DivyaThakur24)
- LinkedIn: [divya-thakurr](https://www.linkedin.com/in/divya-thakurr)
- Portfolio: [divyathakur24.github.io/DivyaThakurPortfolio](https://divyathakur24.github.io/DivyaThakurPortfolio/)
