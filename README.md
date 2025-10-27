# Stock_Price_prediction_model

#  Stock Market Prediction using Machine Learning

##  Overview
This project builds and tests a **machine learning model** (Random Forest or Gradient Boosting) to predict **stock market trends** using historical price data and technical indicators.

The goal is to simulate a realistic stock trading strategy and understand the **limitations of predictive modeling** in noisy financial markets.



##  Features
- Historical stock data pulled from **Yahoo Finance**
- Technical indicator generation (SMA, RSI)
- **Random Forest** classifier for trend prediction
- Simple **backtesting engine** to simulate trading
- Performance evaluation using **Sharpe Ratio**, total returns, and accuracy
- Discussion of **limitations** and **improvement strategies**

## Limitations
- Market Noise and Non-Stationarity

  Financial markets are non-stationary — relationships between variables change constantly.

  A model trained on past data may fail when the market regime shifts (e.g., inflation spikes, global events).
- Overfitting

  Random forests and gradient boosting can overfit small or volatile datasets, memorizing noise instead of learning patterns.






