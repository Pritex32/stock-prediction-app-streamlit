# Project Overview
This projects builds a Stock Price Prediction App using Streamlit and machine learning techniques. The app fetches historical stock price data for GBPUSD=X (British Pound to US Dollar exchange rate) and performs the following:

Data Retrieval and Preprocessing:

Uses yfinance to download historical data from 2010 to 2024.
Handles missing values, scales the data with MinMaxScaler, and creates input-output sequences for modeling.
Visualization:

Plots the stock's opening price and a 50-day rolling average for trend analysis.
Compares actual vs. predicted stock prices and future forecasts using line plots.
Model Development:

Implements an LSTM neural network with three layers and dropout regularization for time-series forecasting.
Trains the model using scaled input data and evaluates it on test data.
Model Evaluation:

Measures performance using Root Mean Squared Error (RMSE).
Prediction and Forecasting:

Predicts stock prices for test data and inversely transforms them back to original scale.
Generates a 60-day future forecast and visualizes the results.
Interactive UI:

Enables users to input stock IDs and view data, visualizations, predictions, and future forecasts directly in the app.# stock-prediction-app-streamlit
