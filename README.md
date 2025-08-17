# **Airline Passengers Ticket Sales Prediction**

This project forecasts airline ticket demand using time series techniques on monthly passenger data.

## **Project Overview**
- **Objective**: Predict ticket sales with ARIMA, SARIMA, Prophet, and XGBoost to capture seasonal trends.
- **Dataset**: `Airlines Passenger.csv` with 144 monthly passenger records.

## **Methodology**
- **Preprocessing**: Loaded data via pandas, used ADF test and differencing for stationarity.
- **Decomposition**: Analyzed level, trend, seasonality, and residuals for pattern insights.
- **Models**:
  - ARIMA: Modeled autoregressive and moving average components.
  - SARIMA: Extended for seasonality.
  - Prophet: Flexible handling of seasonal trends.
  - XGBoost: Applied ensemble learning for forecasting.

## **Results**
- **Prophet**: Achieved 14.27% MAPE, outperforming SARIMA’s 19.23% MAPE.
- **XGBoost**: Recorded RMSE of 69.16 and MAE of 54.53 on validation set.

## **Recommendations**
- Prioritize Prophet for accurate seasonal forecasting.
- Enhance XGBoost with feature engineering for complex trends.
