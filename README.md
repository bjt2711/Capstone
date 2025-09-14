Predictive Modeling of HDFC Bank Stock Price Using R



This project is a Capstone submission for the MSBA program at Kent State University. It focuses on short-term stock price forecasting using minute-level data of HDFC Bank. The main goal is to use predictive modeling, feature engineering, and an interactive dashboard to support financial decision-making.

📌 Objective


Forecast the short-term stock price of HDFC Bank using statistical and machine learning models.

Evaluate model performance on intraday data using technical indicators.

Build a dynamic R Shiny dashboard for real-time forecasting.


📊 Dataset

Source: Intraday trading data for HDFC Bank (1-minute frequency)
Features: OPEN, HIGH, LOW, CLOSE, VOLUME
Engineered Indicators: MA60, Volatility60, RSI, Bollinger Bands, Log Returns


🔍 Exploratory Analysis

STL decomposition of CLOSE price
Volatility clustering detection
Feature correlation and visual analysis


⚙️ Models Used

ARIMA: Linear time series model for baseline comparison
Random Forest: Nonlinear regression model with feature importance extraction
Sliding Window Forecasting: Pattern-based prediction using rolling historical windows


🧠 Feature Engineering

Moving averages (MA60)
Rolling volatility (Volatility60)
Momentum indicator (RSI)
Bollinger Bands for upper/lower price range prediction


📈 Evaluation Metrics

Model	  RMSE	MAE	MAPE

ARIMA	  11.37	7.25	1.51%

RF	 4.94	3.61	0.49%


🖥️ R Shiny Dashboard

Built for manual and pattern-based input forecasts
Real-time predictions with slider controls
Visualization of actual vs predicted prices
Supports trader experimentation and what-if analysis


📌 Tools & Libraries

randomForest, forecast, lubridate, zoo, TTR, shiny, ggplot2


✅ Key Findings

Random Forest outperformed ARIMA for minute-level prediction
Feature engineering had a major positive impact
Sliding window pattern learning improved model stability
Visualization and interactivity aided stakeholder understanding


