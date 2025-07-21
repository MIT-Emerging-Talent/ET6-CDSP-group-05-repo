# Data Analysis

This folder contains the analytical notebooks used to derive insights from the dataset and answer the project’s core research questions.

## Analysis Strategy

We aim to explain the **change in math proficiency (2019–2023)** among primary school students by investigating its relationship with multiple potential factors, including:

- Changes in *completion rate*
- Changes in*out-of-school rate*
- Changes in *trained teacher ratio*
- *Government education expenditure* as a percentage of GDP

## Notebook Summary

### dataset_analysis.ipynb

This notebook performs the following tasks:

- Loads the prepared dataset from 0_datasets
- Shows correlation heatmap of key numeric variables
- Builds a **simple linear regression** model:
math_change ~ completion_change
- Builds a **multiple linear regression** model:
math_change ~ completion_change + out_of_school_change + teacher_change + education_expenditure_percent_gdp
- Visualizes:
  - Regression relationship between all variables and math_change
  - Residuals of the multiple regression model

## Tools & Methods

- **Seaborn** for regression visualization
- **Statsmodels** for statistical modeling
- **OLS regression** to examine potential explanatory variables
- **Residual plots** to check model assumptions

## Notes

The dataset was **not modified** during the analysis.
All results are replicable using the notebook in this folder.
