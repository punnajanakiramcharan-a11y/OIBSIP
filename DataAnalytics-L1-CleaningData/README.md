# Cleaning Data — Titanic Dataset

## Objective
Clean a messy real-world dataset (Titanic passenger data) to make it analysis-ready, documenting every decision made.

## Dataset
Titanic dataset, sourced from Kaggle (891 rows, 12 columns).

## Steps Performed
1. Loaded dataset and generated a data quality report (nulls, duplicates, dtypes)
2. Handled missing values:
   - Age (177 missing): filled with median
   - Embarked (2 missing): filled with mode
   - Cabin (687 missing, ~77%): column dropped
3. Checked for duplicate rows: 0 found
4. Checked Sex and Embarked for inconsistent formatting: none found
5. Verified data types: all columns already correctly typed
6. Outlier detection (IQR method) on Age and Fare: outliers identified and kept, with justification
7. Produced a before/after summary table
8. Saved cleaned dataset as `cleaned_titanic.csv`

## Tools Used
Python, pandas, Google Colab

## Files in this folder
- `cleaning_data_titanic.ipynb` — the Jupyter notebook with all code and analysis
- `cleaned_titanic.csv` — the final cleaned dataset
- `README.md` — this file
