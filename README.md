# Wine Quality Analysis 🍷

This project explores the chemical and physical factors that influence the quality of red and white wines. Using datasets from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality), this analysis aims to identify the key components that contribute to high wine quality and examine differences in rating standards between red and white wine types.

## Files Included

- `INFO 6105 Final Project Shaofan Wei 3.ipynb` – The complete Jupyter Notebook with data preprocessing, EDA, PCA, regression analysis, and visualization.
- `winequality-red.csv` – Dataset of red wine samples.
- `winequality-white.csv` – Dataset of white wine samples.

## Objectives

1. Identify which physical and chemical properties characterize high-quality red and white wines.
2. Determine whether different rating standards exist between red and white wines.

## Methodology

- **Exploratory Data Analysis (EDA)** for identifying important features.
- **Principal Component Analysis (PCA)** to reduce dimensionality and highlight major contributing components.
- **Linear Regression Models** to predict wine quality and evaluate feature impact.
- **Visualization Techniques** like heatmaps and box plots to reveal correlations.

## Key Findings

- **Alcohol content** is strongly positively correlated with wine quality.
- **Density** is negatively correlated with quality, especially in red wine.
- PCA showed red wine characteristics are easier to compress into fewer components, while white wine may require more complex modeling.
- Regression models performed better on red wine than white, suggesting non-linear patterns in white wine data.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
