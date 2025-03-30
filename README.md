# Predictive Model for S&P 500 Buy and Sell Signals

This project provides a machine learning-based framework to predict short-term buy and sell signals for selected S&P 500 stocks. It leverages historical data and technical indicators to forecast future returns and generate actionable trading insights.

## Project Overview

- **Goal**: Predict 5-day future returns and classify signals as Buy, Hold, or Sell
- **Assets**: Includes stocks like AAPL, MSFT, AMZN, META, GOOGL, TSLA, and more
- **Approach**: Feature engineering and classification models (Logistic Regression, Random Forest)

## Features & Models

- **Input Features**:
  - Daily returns
  - 10-day momentum indicators
  - Scaled and cleaned numeric data

- **Target Variable**:
  - `1` → Buy
  - `0` → Hold
  - `-1` → Sell

- **Models Used**:
  - Logistic Regression
  - Random Forest Classifier

## Evaluation

- Accuracy and confusion matrix
- Precision/Recall for buy and sell signals
- Cross-validation to ensure robustness
