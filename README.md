# EV Sales Prediction

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)]()
[![Tech Stack](https://img.shields.io/badge/stack-Python%20|%20Pandas%20|%20ScikitLearn%20|%20Jupyter-green)]()

**EV Sales Prediction** is a machine learning project focused on forecasting future electric vehicle (EV) sales using historical EV adoption, stock, emissions, and population datasets.  
It leverages **classical machine learning regression models** to analyze trends and predict sales, with all steps documented in a **Jupyter Notebook** for transparency and reproducibility.

---

## Overview

The goal is to integrate and analyze EV-related datasets and build **predictive models** for future EV sales.  
The project:

- Cleans and merges multiple CSV datasets (IEA EV sales, stock, CO₂ emissions, population),
- Performs **exploratory data analysis (EDA)** with visualizations,
- Builds **Linear Regression** and **Random Forest** models to forecast EV sales,
- Evaluates models using **Mean Squared Error (MSE)** and **R² score**,

---

## Features

- **Data Preprocessing**: Cleans and integrates EV sales, stock, emissions, and population data.
- **Exploratory Visualizations**: Global and category-wise EV adoption trends.
- **Machine Learning Forecasting**:
  - **Linear Regression** for baseline predictions.
  - **Random Forest Regressor** for more flexible, non-linear predictions.
- **Evaluation Metrics**:
  - MSE (Mean Squared Error),
  - R² Score (Goodness of Fit).
- **Interactive Notebook**:
  - `dea_project.ipynb` — step-by-step workflow,
  - `dea_project.html` — shareable export.

---

## Tech Stack

- **Programming Language**: Python 3.9+
- **Libraries**:
  - pandas, numpy (data processing),
  - matplotlib, seaborn (visualization),
  - scikit-learn (Linear Regression, Random Forest),
  - statsmodels (statistical checks),
  - Jupyter Notebook for analysis.

---

## Datasets

Included data sources:

- `Global.csv` — Worldwide EV sales/adoption stats.
- `IEA-EV-dataEV ...` — Historical EV sales/stock for **cars, vans, trucks, buses**.
- `Population.csv` — Population trends (for normalization).
- `International Energy Agency - CO2 emissions by sector in Germany.csv` — Context data.
- `combined_data.csv` — Final merged and cleaned dataset.

---
