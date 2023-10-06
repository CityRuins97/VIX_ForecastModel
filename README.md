# CBOE Volatility Index Forecast Model

*Mentor: Rohit Khurana From Morgan Stanley*

*

## Abstract
Background: CBOE Volatility Index (VIX) time-series dataset including daily open, close, high
and low. The CBOE Volatility Index (VIX) is a key measure of market expectations of near-term
volatility conveyed by S&P 500 stock index option prices introduced in 1993.
leverage publicly available data for VIX and macroeconomic variables, CCAR Stress
Testing Scenarios data, to build a model to predict stock market volatility.

## Setup

Required skills include knowledge of time series analysis, regression, machine
learning, finance and programming in a statistical language such as SAS, Python, or R.

## Structure

• Start with web scraping of required dataset
• Conduct data processing steps including stationarity and seasonality analysis,
supported with statistical analysis
• Use time series analysis to build the model using different techniques including
autocorrelation, partial autocorrelation (ARIMA, SARIMA, etc.)
• Add exogenous variables like (GDP USA, Inflation, SOFR, etc.) to the above model to
improve predictability
• Later, use machine learning technique (neural network, random forest, etc.) to improve
the model performance
• Further, use mean reversion technique to predict VIX index and compare the results
• Conduct in-sample and out-sample backtesting
• Use CCAR Scenarios 2023 to forecast the VIX for next 9 quarters
• Compare the results with Market Volatility forecast available as part of Stress Testing
CCAR Scenarios 2023 (baseline and severely adverse)
• Conduct sensitivity analysis on the champion and challenger model

## References
