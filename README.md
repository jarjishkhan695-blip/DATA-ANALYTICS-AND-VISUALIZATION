# DATA-ANALYTICS-AND-VISUALIZATION
ARIMA-based time series forecasting of BANKINDIA stock using NSE historical data with ADF test and ACF/PACF analysis
# 📊 BANKINDIA Stock Price Forecasting using ARIMA

## 📌 Objective
To analyze and forecast stock prices of BANKINDIA using ARIMA model.

## 📂 Dataset
Data collected from NSE (1 year historical data).

## 🔧 Data Preprocessing
- Converted date to datetime format
- Handled missing values using forward fill
- Sorted data chronologically

## 📈 Visualization
Closing price trend plotted

## 📊 Stationarity Test
- ADF Statistic: -3.32  
- p-value: 0.0138  
- Conclusion: Data is stationary

## 🔍 Model Selection
- ACF & PACF analyzed
- Selected ARIMA(1,0,1)

## 🤖 Model Performance
- Model fitted successfully
- AIC used for evaluation

## 🔮 Forecasting
- Predicted next 30 days closing prices

## 📊 Results
- Stable trend observed
- No strong seasonal pattern

## ⚖️ AI Ethics & Responsible Usage
- Data is publicly available
- No misleading claims
- Forecasts are not financial advice

## 📌 Conclusion
ARIMA model effectively captured the stock behavior and provided short-term forecasts.

