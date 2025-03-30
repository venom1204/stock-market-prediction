# Stock Market Prediction Application

## Overview
This application predicts stock prices using a hybrid CNN-LSTM model, integrating historical stock data and Twitter sentiment analysis.

## Features
- **Stock Price Forecasting**: Predicts Open and Adj Close prices.
- **Sentiment Analysis Integration**: Enhances predictions using Twitter sentiment data.
- **Visualization Tools**: Provides detailed trend analysis.
- **Model Training & Evaluation**: Includes training, validation, and testing pipelines.
- **Save/Load Models**: Supports saving and reusing models.

## Dataset
Uses stock data from Jan 2018 - July 2022 with key columns:
- **Date, Open, High, Low, Close, Adj Close**: Stock price metrics.
- **Volume**: Trading volume.
- **P_mean, P_sum**: Sentiment analysis metrics.
- **twt_count**: Number of relevant tweets per day.

## Model Architecture
A hybrid **CNN-LSTM** model:
- **Convolutional Layers**: Capture short-term patterns.
- **LSTM Layers**: Identify long-term dependencies.
- **Dense Layers**: Make final predictions.
