# Machine Learning Approaches: Stock Price Prediction using Technical & News Sentiment Analysis

## General

Welcome to the **AAPL Stock Price Predictor (Python) Repository**, the central hub for this project.

**Original Author**: Foivos Gaitantzis

<img src="https://avatars.githubusercontent.com/u/47535153?v=4" width="20%" height="20%" alt="Global Recruits Logo">

## Project Description

This project aims to predict the prices of Apple Stocks (NASDAQ: AAPL) by extracting relevant features from sentiment data derived from various news sources as well as technical indicators from time-series data of historic price and volume. The proposed algorithm is written in Python and makes use of two fundamental machine learning libraries; Scikit-Learn & TensorFlow.

The use of various sentiment analysers is proposed to aggregate the emotion portrayed by various headlines and normalize them to an average daily value. These daily values are then merged with historical prices and technical indicators such as the Relative Strength Index (RSI) and the Moving Average Convergence-Divergence (MACD) over a short and long-term period.

Three machine learning algorithms are experimented: Linear Regression, Support Vector Regression (SVR) & Long Short-Term Memory (LSTM) recurrent neural networks. Hyperparameters are tuned accordingly and the models are evaluated using the Root Mean Squared Error (RMSE) and the Mean Absolute Percentage Error (MAPE).

An algorithmic trading bot is built using the most promising algorithm indicating to what extent day trading predictions can be used to yield profit.

## Key Components

This repository contains the following essential components:

- Data Sources: Integration with various news sources and stock market APIs for collecting data.

- Sentiment Analysis: Code for extracting sentiment features from news headlines and aggregating them into daily sentiment scores.

- Technical Indicators: Implementation of technical indicators like the Relative Strength Index (RSI) and Moving Average Convergence-Divergence (MACD) to derive relevant features.

- Machine Learning Models: Three primary machine learning algorithms - Linear Regression, Support Vector Regression (SVR), and Long Short-Term Memory (LSTM) recurrent neural networks - for predicting stock prices. Utilization of Scikit-Learn and TensorFlow for model development and training.

- Evaluation Metrics: Calculation and reporting of Root Mean Squared Error (RMSE) and Mean Absolute Percentage Error (MAPE) to assess model performance.

- Algorithmic Trading Bot: Code for building a trading bot that utilizes the most promising algorithm to evaluate the potential profitability of day trading predictions.

## Disclaimer

This repository is intended for educational and research purposes only. It provides insights into the development of a stock price prediction system and algorithmic trading bot. It is not meant for production use, and no support or updates will be provided. Users are encouraged to use this repository responsibly and in compliance with relevant legal and ethical guidelines.