# Mobile Plan Recommendation

## Business problem

Recommend the most suitable mobile plan from customer usage behavior using binary classification.

## Approach

- Split the data into training, validation, and test samples.
- Compared Decision Tree, Random Forest, and Logistic Regression models.
- Tuned tree depth and the number of estimators on validation data.
- Compared model performance with the majority-class baseline.

## Result and recommendation

Random Forest produced the strongest validation accuracy at approximately **0.813**. The final test score must be regenerated after correcting the original notebook’s test-set training error; no unsupported replacement metric is reported here. In production, use the model only after clean holdout testing and monitoring by customer segment.

## Tools

Python, pandas, scikit-learn

## Notebook

[Open the analysis](mobile_tariffs_eng.ipynb)

## Data availability

The original educational dataset is not included. The notebook expects `users_behavior.csv` in a local `data/` directory.
