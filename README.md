# Loan-Default-Prediction
📌 Overview

This project predicts whether a borrower will default on a loan using machine learning models.
We tested Random Forest and XGBoost, and found XGBoost with threshold tuning gave the best recall (catching most defaulters).

🛠 Tech

Python, Pandas, Scikit-learn

XGBoost, LightGBM, RandomForest

Joblib (for saving models)

🔑 Key Points

Preprocessed dataset (missing values, scaling, feature engineering).

Tuned XGBoost with custom decision threshold (0.3).

Achieved ~77% recall on default cases.

Model, scaler, and features saved for reuse.
