# StockSavant
Stock Prediction Website Application

The purpose of this project is to make a stock trend predictor.
This code predicts stock data of the stock that has been entered by the user. Stock history is pulled from Yahoo Finance via Pandas Datareader. The predictor is made as a website application via streamlit(library).
From the pulled stock data history, the first 70% of the stock history is used to train the data. The last 30% of the pulled data is used for testing purposes.
