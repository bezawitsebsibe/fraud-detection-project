# Fraud Detection Project (Week 8 - Interim 1)

## Overview
This project is aimed at detecting fraud in e-commerce and bank transactions. I used the `Fraud_Data.csv`, `IpAddress_to_Country.csv`, and `creditcard.csv` datasets.

## What I’ve Done So Far
- ✅ Loaded and cleaned the data
- ✅ Converted time columns and removed duplicates
- ✅ Engineered features like `time_since_signup`, `hour_of_day`, and `day_of_week`
- ✅ Mapped IP addresses to countries using IP range
- ✅ Conducted exploratory data analysis (EDA)
- ✅ Analyzed class imbalance in the datasets

## Next Steps
- Handle class imbalance during model training
- Build Logistic Regression and XGBoost/Random Forest models
- Use SHAP for model explanation

## How to Run
- Clone the repo
- Open `notebooks/1-data-cleaning.ipynb`
- Run all cells
