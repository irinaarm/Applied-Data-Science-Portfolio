# Borrower Default Risk Analysis

## Business problem

Identify borrower characteristics associated with delayed loan repayment to support credit-risk assessment.

## Approach

- Cleaned missing, anomalous, and duplicate records.
- Standardized categorical values and grouped loan purposes.
- Compared default rates by number of children, marital status, income group, and loan purpose.

## Result and recommendation

The analysis identified meaningful differences in repayment behavior across borrower segments. Property-related borrowers showed comparatively strong repayment discipline, while some car-loan and higher-risk demographic segments had higher default rates. These findings can support a broader scoring model, but small subgroups should not be used as standalone approval rules.

## Tools

Python, pandas, PyMystem3

## Notebook

[Open the analysis](data_preprocessing_eng.ipynb)

## Data availability

The original educational dataset is not included. To reproduce the notebook, place `data.csv` in a local `data/` directory and update the loading cell if required.
