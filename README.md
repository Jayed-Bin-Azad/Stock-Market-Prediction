# Stock Market Prediction using LSTM

## Overview

This project aims to predict the values of the stock market using Long Short-Term Memory (LSTM) models. The LSTM model is a type of recurrent neural network (RNN) known for its ability to learn long-term dependencies and patterns in sequential data, making it well-suited for time series prediction tasks like stock market forecasting.

# How to Install and Run the Project 
  1. Download the raw file
  2. Open Jupyter Notebook and open the raw downloaded file
  3. Run the codes from Jupyter Notebook

## Key Features

- **Predictive Capability:** The LSTM model enables investors to predict the future values of the stock market based on historical data.
  
- **Trend Analysis:** By analyzing the output of the LSTM model, investors can gain insights into the ongoing trends in the stock market, helping them make informed decisions.

- **Profitability Evaluation:** The model allows investors to determine whether a particular trade or investment strategy is likely to be profitable or not, assisting in risk management and decision-making.

## How LSTM Model Predicts the Values

The LSTM model predicts the values of the stock market by learning from historical data patterns and relationships. It consists of multiple LSTM cells that process sequential input data, such as historical stock prices, and generate predictions for future values. The model is trained using a dataset comprising historical stock market data and corresponding target values. During training, the model adjusts its internal parameters to minimize the difference between its predictions and the actual values. Once trained, the LSTM model can be used to make predictions for unseen data, providing valuable insights for investors.

## Usage

To use the LSTM model for stock market prediction, follow these steps:

1. **Data Collection:** Gather historical stock market data for the desired company.

2. **Data Preprocessing:** Preprocess the data by cleaning, normalizing, and transforming it into a suitable format using Min-Max Scaler for training the LSTM model.

3. **Model Training:** Train the LSTM model using the 70% preprocessed data.

4. **Prediction:** Once the model is trained, use it to make predictions for future stock market values using the 30% of preprocessed Data. Evaluate the model's performance using metrics such as Root Mean Square Error (RMSE).

5. **Decision Making:** Analyze the model's predictions and incorporate them into investment decisions, considering factors such as risk tolerance, market conditions, and investment goals.

## Contributors

- Jayed Bin Azad (@jayed-bin-azad): Project Lead, Data Collection , Data Preprocessing , Model Training , Testing ,  Documentation
