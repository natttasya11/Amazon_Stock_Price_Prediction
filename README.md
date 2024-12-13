# Amazon Stock Price Prediction

This project predicts Amazon's stock prices using Linear Regression in Python. The model forecasts stock price trends based on historical data and features like year fractions, daily price fluctuations, and past closing prices. The predictions extend up to the year 2025.

## Features

- **Data Preprocessing:** 
  - Data cleaning by removing irrelevant rows.
  - Date format conversion for proper analysis.
  - Handling missing values by replacing or removing.

- **Model:** 
  - Linear Regression used for stock price prediction.
  - Incorporates year fractions and daily price fluctuations into the model.

## Libraries Used

- **numpy:** For numerical operations and creating arrays.
- **pandas:** For data manipulation and analysis, including reading CSV data and cleaning.
- **matplotlib:** For visualizing the data and predictions.
- **sklearn.linear_model:** For implementing Linear Regression.

## Dataset

The dataset used for this project is historical stock data for Amazon, which includes columns such as date, adj close, open, high, low, prices, volume. The data is also available in this repository in the file named Amazon_Stock_Data.csv.


