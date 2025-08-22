# Sales Forecasting
Task 3 @ Elevvo ML Internship

## Instructions
1. Dataset (Recommended): Walmart Sales Forecast ([Kaggle](https://www.kaggle.com/)).
2. Predict future sales based on historical sales data.
3. Create time-based features (day, month, lag values).
4. Apply regression models to forecast next period's sales.
5.Plot actual vs. predicted values over time.

### Bonus:
1. Use rolling averages and seasonal decomposition.
2. Apply XGBoost or LightGBM with time-aware validation.

## Dataset
- [Sales Forecasting](https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast)

## Notebook
- [Sales Forecasting](https://github.com/Asma-Nasr/Sales-Forecasting/blob/main/sales_forecasting.ipynb)

## Performance Comparison

| Models                                        | Mean Squared Error | R2 Score  |
|-----------------------------------------------|---------------------|-----------|
| Linear Regression                             | 37871290.84         | 0.92616   |
| XGBoost                                       | 11324349.62         | 0.97792   |
| LGBM                                          | 14459745.28         | 0.97180   |
| Linear Regression with Scaled data           | 0.00                | 0.92616   |
| XGBoost with Scaled Data                     | 0.00                | 0.97767   |
| LGBM with Scaled Data                        | 0.00                | 0.97268   |
| XGBoost Hyperparameter Tuned                  | 10539729.03         | 0.97945   |
| LGBM Hyperparameter Tuned                     | 10717770.84         | 0.97910   |
| XGBoost Hyperparameter Tuned and Data Scaled | 0.00                | 0.97914   |
| LGBM Hyperparameter Tuned and Data Scaled    | 0.00                | 0.97916   |
