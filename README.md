# Energy-Consumption-Time-Series-Forecasting

## Task Objective

The objective of this project is to forecast short-term household energy consumption using historical time-series data. By analyzing temporal patterns such as hourly and daily usage, the goal is to build predictive models that can accurately estimate future energy demand.

## Approach

The project follows a structured time-series forecasting workflow:

## Data Understanding & Exploration

Loaded and inspected the Household Power Consumption dataset.
Parsed date and time columns into a proper datetime format.
Analyzed energy usage trends over time.

## Data Preprocessing

Handled missing values and cleaned the dataset.
Resampled data to hourly or daily intervals for consistency.
Converted data into time-series format.

## Feature Engineering

Extracted time-based features such as:
Hour of the day
Day of the week
Month
Created additional features to capture temporal patterns.

## Model Development

Applied ARIMA for statistical time-series forecasting.
Used Prophet for trend and seasonality modeling.
Implemented XGBoost for machine learning-based forecasting.

## Model Evaluation

Evaluated models using MAE (Mean Absolute Error).
Calculated RMSE (Root Mean Squared Error).
Compared model performance to identify the best approach.

## Visualization

Plotted actual vs forecasted energy consumption.
Visualized trends and seasonal patterns.

## Results & Insights

Time-series models successfully captured daily and weekly energy usage patterns.
Prophet effectively modeled seasonality and trends in the data.
XGBoost performed well when time-based features were included.
ARIMA provided a solid baseline for comparison.
Model performance varied depending on how well temporal features were captured.

## Model Insights

Prophet handled seasonality better compared to ARIMA.
XGBoost captured complex patterns when feature engineering was applied.
ARIMA performed well for short-term forecasting but struggled with complex seasonality.
Feature engineering significantly improved machine learning model performance.

## Business Insights

Energy consumption shows clear daily and weekly patterns, which can help optimize energy distribution.
Forecasting allows utility providers to manage supply more efficiently.
Peak usage hours can be identified for better load balancing.
Accurate predictions can reduce operational costs and improve energy planning.

## Conclusion

This project demonstrates the effectiveness of time-series forecasting techniques in predicting energy consumption. By comparing statistical, machine learning, and hybrid approaches, valuable insights were gained into temporal patterns and model performance. The results highlight the importance of feature engineering and model selection in time-series analysis.

## Future Improvements

Use LSTM or deep learning models for improved forecasting.
Perform hyperparameter tuning for better accuracy.
Incorporate weather or external data for enhanced predictions.
Deploy the model for real-time forecasting applications.

##Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Statsmodels (ARIMA)

Prophet

XGBoost

Jupyter Notebook


