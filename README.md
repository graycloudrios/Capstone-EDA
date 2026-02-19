# Capstone Assignment 20.1 — Initial Report & EDA (Classification)

## Summary (Initial Findings)
This project frames **industry growth prediction** as a **binary classification** task:

- **Target (`GrowthLabel`)**:  
  - `1` if an industry's next-year annual average employment is higher than the current year  
  - `0` otherwise
- The dataset was cleaned (duplicates removed, numeric conversion, filtering of non-employment percentage rows, and missing values imputed).
- Monthly employment was reshaped to long format and aggregated to **annual averages** per industry.
- Feature engineering produced lag and trend features (lag1, YoY change, rolling mean, trend slope, log transform).
- A **Logistic Regression** baseline model was trained and evaluated using **F1-score** (primary) and ROC-AUC (secondary).

## Files
- Notebook: `Capstone_20_1_Initial_Report_EDA.ipynb`
- Data: `EDD-Data.csv`

## Open the Notebook
Open [`Capstone_20_1_Initial_Report_EDA.ipynb`](Capstone_20_1_Initial_Report_EDA.ipynb) in Jupyter Lab/Notebook.
