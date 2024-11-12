# Stock Price Predictor

## Overview

The Stock Price Predictor is a Python application that predicts the closing price of stocks using historical data. It utilizes the `yfinance` library to fetch stock data and employs a linear regression model from `scikit-learn` to make predictions. The application features a user-friendly GUI built with Tkinter, allowing users to input a stock symbol and receive a predicted closing price along with a visual representation of the stock's historical prices.

## Features

- Fetches historical stock data from Yahoo Finance.
- Predicts the closing price of a stock using a linear regression model.
- Displays the actual closing prices and the predicted price in a graphical format.
- User-friendly interface for easy interaction.

## Requirements

To run this application, you need the following Python packages:

- `tkinter` (included with Python standard library)
- `yfinance`
- `pandas`
- `scikit-learn`
- `matplotlib`

You can install the required packages using pip:

```bash
pip install yfinance pandas scikit-learn matplotlib
