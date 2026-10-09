# Sprint 3 — Advanced modeling (Telco churn)

Feature engineering, model benchmarking, light hyperparameter search, coefficient interpretability, and a model card.

## What’s in the notebook
- Engineered features: tenure_years, num_services, long_contract, avg_charge_per_tenure
- Benchmarks: Logistic, Random Forest, XGBoost
- GridSearchCV on Logistic (best C = 1)
- Coefficient importances + chart
- Ethical model card

## Main test results
- Best model: Logistic accuracy ~0.81, Yes recall ~0.56
- RF and XGBoost did not beat logistic on this split
