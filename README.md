# fraud-detection
Credit card fraud detection: from EDA and a cost-sensitive model to a served, monitored API.

## Goal
Detect fraudulent card transactions under heavy class imbalance (~0.17% fraud), choose the decision threshold by business cost, and serve the model with monitoring.

## Data
[Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) (Kaggle, ULB): 284,807 European card transactions with PCA features V1-V28. Data is not committed to this repo.

## Planned architecture
EDA notebook -> src/train.py (scikit-learn, LightGBM) -> MLflow tracking -> FastAPI service in Docker -> drift monitoring.

## Status
- [ ] EDA
- [ ] Logistic regression baseline
- [ ] LightGBM with cost-based threshold

## How to run
To be added.
