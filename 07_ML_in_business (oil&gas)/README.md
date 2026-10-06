# Machine Learning for Business Decisions

## Business problem

Select the oil-production region expected to deliver the highest profit while keeping the probability of loss within acceptable limits.

## Approach

- Trained Linear Regression models to predict reserves in three regions.
- Ranked candidate wells and calculated break-even economics.
- Estimated profit distributions and downside risk using 1,000 bootstrap samples.

## Final result

Region 2 achieved mean predicted profit of **0.515 billion** monetary units, a **95% confidence interval of 0.069–0.932 billion**, and an estimated **1.0% risk of loss**.

## Business recommendation

Prioritize Region 2 because it combines the highest expected profit with the lowest estimated downside risk.

## Tools

Python, pandas, NumPy, SciPy, scikit-learn, Matplotlib, Seaborn

## Notebook

[Open the analysis](project_oil_wells_eng.ipynb)

## Data availability

The original educational datasets are not included. The notebook expects `geo_data_0.csv`, `geo_data_1.csv`, and `geo_data_2.csv` in a local `data/` directory.
