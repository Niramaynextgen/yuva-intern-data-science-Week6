# yuva-intern-data-science-Week6


## Project Overview
This project evaluates machine-learning models that predict beauty and wellness product ratings. It builds on the earlier project using `Rating` as the target variable.

## Dataset
Use the same `beauty_wellness.csv` file used in Week 5. Expected columns may include product brand, category, usage frequency, price, rating, number of reviews, product size, skin type, gender target, packaging, ingredient, cruelty-free status, and country of origin.

**Target column:** `Rating`

Do not use a different dataset unless your mentor instructs you to. If the CSV has a different filename, update `DATA_FILE` in the Python script.

## Models Evaluated
- Mean Baseline
- Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor

## Evaluation Metrics
- **MAE (Mean Absolute Error):** average absolute prediction error in rating points; lower is better.
- **RMSE (Root Mean Squared Error):** penalizes large errors more strongly; lower is better.
- **R² (R-squared):** indicates how much variation the model explains relative to a mean-only reference; closer to 1 is generally better, and it can be negative.
- **Cross-validation:** repeats evaluation across training folds to assess stability.

Accuracy, F1-score, and AUC-ROC are classification metrics and are not appropriate for this continuous rating-prediction setup unless ratings are first converted into defined classes.

## Requirements
Python 3.9 or newer is recommended.