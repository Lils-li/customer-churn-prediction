# Customer Churn Prediction

## Project Overview
This project aims to predict customer churn using classical machine learning models. The goal is to estimate the probability that a customer will leave (churn) based on tabular data.

**Metric:** ROC-AUC

## Dataset
The project uses three datasets:
- `train.csv` – Training data with features and target (`Churn`)
- `test.csv` – Test data without target
- `submission.csv` – Example submission file

## Methodology
1. **Exploratory Data Analysis (EDA)** – Understand data distributions, missing values, and feature types.
2. **Data Preprocessing** – Encode categorical features, normalize numerical features, handle IDs.
3. **Modeling** – Train Logistic Regression and CatBoost models. Use cross-validation and hyperparameter tuning.
4. **Evaluation** – Compare models using ROC-AUC, confusion matrix, and classification report.
5. **Prediction** – Generate churn probabilities for the test dataset.

## Files
- `datasets/` – Contains `train.csv`, `test.csv`, and `submission.csv`.
- `notebook/customer_churn_analysis.ipynb` – Jupyter notebook with full analysis and modeling.
