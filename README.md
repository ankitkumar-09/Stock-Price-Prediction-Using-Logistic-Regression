# Stock-Price-Prediction-Using-Logistic-Regression

📈 Stock Price Prediction using Logistic Regression
This project aims to predict the next day's stock price movement (Up/Down) using Logistic Regression based on historical stock data. The dataset is fetched from Yahoo Finance (yfinance), and the model is trained to classify whether the stock price will go up (1) or down (0).

🚀 Features of the Project
Data Collection 📊: Fetches stock market data using yfinance.
Feature Engineering 🛠: Creates relevant features such as Open, High, Low, Close, and Volume.
Target Variable 🎯: Determines if the next day's closing price is higher (1) or lower (0) than today's.
Model Training 🤖: Implements Logistic Regression to predict stock movement.
Evaluation 📈: Computes accuracy and classification metrics.
📂 Dataset Details
The dataset is obtained from Yahoo Finance using the yfinance library. It contains the following columns:

Feature	Description
Date	Trading date (Index)
Open	Opening price of the stock
High	Highest price during the day
Low	Lowest price during the day
Close	Closing price of the stock
Volume	Number of shares traded
We create an additional column:

Target (1 if the next day's closing price is higher, 0 otherwise).
