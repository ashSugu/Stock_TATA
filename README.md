IITM x DTL Project member app

This project focuses on predicting **daily returns of Tata Motors stock** using financial time series data and alternative signals. It is part of my exploration in **Quantitative Finance** and combines classical financial indicators with machine learning to uncover predictive insights from historical stock prices.

## Project Objective

To build a predictive model for Tata Motors stock returns using:

- Cleaned and processed OHLCV data
- Technical indicators like RSI, EMA, Bollinger Bands
- Feature engineering based on lagged values and volatility
- Machine learning regression (Random Forest Regressor)
- Model evaluation with RMSE and R² metrics

## Workflow Summary

1. **Data Preparation**
   - Historical OHLCV data (Open, High, Low, Close, Volume)
   - Datetime parsing and setting proper time index

2. **Feature Engineering**
   - Lag features
   - Moving Averages (SMA, EMA)
   - Relative Strength Index (RSI)
   - Rolling standard deviation (volatility)
   - Moving Average Convergence Divergence (MACD)
  
3. **Performaing Analysis**
   - Correlation
   - Granger Causality Test

3. **Modeling**
   - Train-test split (time aware split)
   - Model: RandomForestRegressor
   - Evaluation using **Root Mean Squared Error** and **R² Score**

