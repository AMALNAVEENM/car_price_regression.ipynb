# Car Price Prediction – Data Science Assignment

Predicts car prices using the `CarPrice_Assignment.csv` dataset.

## Requirements
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
Files
car_price_regression.ipynb – Main notebook
CarPrice_Assignment.csv – Dataset
Models Evaluated
Linear Regression
Decision Tree
Random Forest (Best)
Gradient Boosting
SVR
Key Findings
Top features: brand, enginesize, curbweight
Random Forest R²: ~0.96
Hyperparameter tuning improves generalization
Model
R²
MSE
MAE
Random Forest
~0.95–0.97
~400k–600k
~400–500
Gradient Boosting
~0.93–0.95
~600k–800k
~500–600
Decision Tree
~0.89–0.92
~1.1M
~1000
Linear Regression
~0.80–0.85
~2.5M+
~1300+
SVR
~0.75–0.82
~3M+
~1500+
