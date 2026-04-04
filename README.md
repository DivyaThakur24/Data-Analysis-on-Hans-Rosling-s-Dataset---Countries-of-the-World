# Data Analysis on Hans Rosling's Dataset - Countries of the World

![CoverPic](https://user-images.githubusercontent.com/36337727/179342592-941a0dd2-6cee-4d8d-ade9-0eb3ddb9cffc.png)

Exploratory data analysis and visualization project based on a countries-of-the-world dataset containing population, GDP, literacy, mortality, land use, climate, and economic sector indicators.

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
