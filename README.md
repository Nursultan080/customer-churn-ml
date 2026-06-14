# Customer Churn Modeling

A machine learning project that predicts whether a telecom customer is likely to churn.

## Project Goal

The goal of this project is to build a simple, reproducible classification workflow for customer churn. This is useful because businesses can use churn prediction to identify at-risk customers and plan retention strategies.

## Dataset Source

The project uses the included `telco_v1.csv` dataset, a Telco-style customer churn dataset with customer account information, service usage features, and a churn label.

## Models Used

- Logistic Regression
- Train/validation split
- Standard scaling for numeric features
- Classification metrics: accuracy and ROC-AUC

## Final Results

The final Logistic Regression model reached:

- Validation accuracy: `0.801`
- Validation ROC-AUC: `0.766`

## What I Learned

- How to prepare tabular customer data for a binary classification task
- How to split data into training and validation sets
- How to scale features and train a baseline model
- How to evaluate churn predictions using both accuracy and ROC-AUC

## Tech Stack

- Python
- Jupyter Notebook
- pandas, NumPy
- scikit-learn
- matplotlib/seaborn

## Files

- `customer_churn_modeling.ipynb` - main notebook
- `telco_v1.csv` - dataset
