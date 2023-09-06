# Stock Price Predictor using LSTM

This project predicts the closing stock price of a given company using an Artificial Recurrent Neural Network called Long Short Term Memory (LSTM). The code for this project was developed on Google Colab.

## Description

The program fetches historical stock data using the Yahoo Finance API, scales the data, trains an LSTM model on the training data, and then predicts the stock prices on the test data. The model's predictions are then visualized against the actual stock prices. The project concludes by predicting the next day's stock closing price.

## Dependencies

- math
- pandas_datareader
- numpy
- pandas
- sklearn
- keras
- matplotlib

## Setup & Execution

1. Ensure you have all the required libraries installed. You can install them using pip:
```bash
pip install pandas_datareader numpy pandas sklearn keras matplotlib
```

2. Open the notebook in Google Colab or any Jupyter environment.
3. Run the cells sequentially.

## Features

- Fetching historical stock data from Yahoo Finance API.
- Visualizing the historical closing prices.
- Pre-processing and scaling of stock data.
- Training an LSTM model for stock price prediction.
- Visualizing the actual vs. predicted stock prices.
- Predicting the next day's closing stock price.

## Usage

You can change the stock ticker and date range to predict the stock prices of different companies over different time spans. The current implementation uses the 'INDIGO.NS' stock ticker.

## Note

The LSTM model's architecture, training epochs, batch size, and other parameters can be tuned for better performance or to adapt to different stocks with varying characteristics.
