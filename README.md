# ML Assignment 3 - Data Preprocessing

**Dataset:** IBM Telco Customer Churn  
https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

## Files
- `assignment3_preprocessing.ipynb` - full notebook (Q1-Q12), run top to bottom in Google Colab
- `pipeline.joblib` - fitted preprocessing pipeline (ColumnTransformer inside a Pipeline), saved by Q11

## What the notebook covers
Stratified split first, three missing-value strategies, three outlier rules, one-hot / ordinal / frequency encoding with unseen-category handling, three scalers, log1p and Yeo-Johnson, a ColumnTransformer pipeline, a leakage demonstration, SMOTE on the training set only, and saving/reloading the pipeline.

## How to run
Open the notebook in Colab, use Runtime -> Restart and run all. The first cell installs `imbalanced-learn`.
