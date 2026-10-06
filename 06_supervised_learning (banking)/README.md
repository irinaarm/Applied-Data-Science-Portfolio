# Customer Churn Prediction

## Business problem

Identify bank customers likely to leave so retention activity can focus on high-risk customers before churn occurs.

## Approach

- Cleaned customer data and encoded categorical variables.
- Compared Logistic Regression, Decision Tree, and Random Forest models.
- Addressed class imbalance through weighting, upsampling, and downsampling.
- Evaluated the final model on a held-out test set.

## Final metrics

- **F1:** 0.603, above the required minimum of 0.59
- **ROC-AUC:** 0.86

## Business recommendation

Use Random Forest churn scores to prioritize retention campaigns. Set the intervention threshold using customer value and campaign cost rather than treating every predicted churn case equally.

## Tools

Python, pandas, NumPy, scikit-learn, Matplotlib

## Notebook

[Open the analysis](project_bank_eng.ipynb)

## Data availability

The original educational dataset is not included. The notebook expects `Churn.csv` in a local `data/` directory.
