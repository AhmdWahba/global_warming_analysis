# Global Warming Analysis

This project investigates the relationship between global temperatures, greenhouse gas emissions, and sea level rise over the past six decades. It uses a structured data analysis pipeline implemented in Jupyter Notebook, combining exploratory data analysis (EDA), data cleaning, statistical visualization, and regression modeling.

## Project Objectives

- Perform a comprehensive exploratory data analysis using real-world climate data.
- Identify trends, patterns, and correlations between key climate indicators.
- Apply polynomial regression to forecast global temperature and sea level trends for the next decade.

## Datasets

Three datasets were selected based on coverage, structure, and relevance to the research objectives:

1. **Global Temperature** – (https://www.kaggle.com/datasets/sevgisarac/temperature-change)
2. **Sea Level Rise** – (https://www.kaggle.com/datasets/jarredpriester/global-sea-level-rise)
3. **Greenhouse Gas Emissions** – (https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions), (https://www.kaggle.com/datasets/srikantsahu/co2-and-ghg-emission-data)

## Technical Approach

- Datasets were processed using Pandas and NumPy.
- Regular expressions and validation techniques were used to clean and format the data.
- Outliers and boundary values were analyzed and addressed where appropriate.
- Visualizations were created using Matplotlib and Seaborn to explore relationships between variables.
- Polynomial regression was applied to generate forward-looking estimates for temperature and sea level changes.

## Exploratory Findings

- Clear upward trends were observed in both temperature and sea level indicators.
- Emissions data showed strong correlation with temperature increases.
- Word clouds, descriptive statistics, and correlation matrices were used to highlight key insights.
- Data inconsistencies such as missing values and skewness were handled to ensure reliable results.

## Data Ethics

- All datasets used are publicly available and properly cited.
- No personal or sensitive data was included in the analysis.
- Bias, attribution, and licensing considerations were addressed during data selection and processing.

## Project Files

- `globalwarming.ipynb` – Main analysis notebook
- `global_temp.csv` – Temperature dataset
- `Global_sea_level_rise.csv` – Sea level dataset
- `emission data.csv` – Emissions dataset
- `requirments.txt` – List of Python packages used

## Summary

This analysis contributes to a better understanding of how greenhouse gas emissions relate to long-term shifts in global temperature and sea levels. The code and methodology are fully documented in the notebook to support reproducibility and further development.
