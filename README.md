# R-Stock-Forecasting
## Introduction
This project focuses on analyzing historical stock data of Amazon and developing models to predict future stock prices. Leveraging time series analysis techniques, we aim to identify trends and patterns in the data and utilize ARIMA models to make accurate predictions.

## Methodology
Here's an overview of the methodology employed in this project:

Data Extraction: We start by extracting historical stock data from Yahoo Finance using the quantmod package in R.

Exploratory Data Analysis (EDA): Next, we explore and visualize the data to gain insights into underlying trends and patterns. We utilize autocorrelation functions (ACFs) and partial autocorrelation functions (PACFs) to understand the autocorrelation structure of the time series data.

Stationarity Analysis: We conduct stationarity tests to ensure that the time series data is stationary, which is a prerequisite for applying ARIMA models.

Model Building: We proceed to build an ARIMA (AutoRegressive Integrated Moving Average) model, a popular time series forecasting technique, to predict future stock prices. Additionally, we set the ARIMA model to seasonal to account for any seasonal patterns in the data.

Model Evaluation: Finally, we evaluate the performance of the ARIMA model and interpret the results to assess its accuracy in predicting Amazon stock prices.

## Importing Required Packages
Here are the key packages used in our analysis:

tseries: Provides tools for time series analysis, including statistical tests and data manipulation functions.
forecast: Used for time series forecasting, offering functions for model estimation, prediction, and evaluation.
TTR (Technical Trading Rules): Facilitates technical analysis by computing various financial indicators.
quantmod: Enables financial modeling and quantitative analysis, including downloading financial data and backtesting trading strategies.
