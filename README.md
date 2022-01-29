# Cryptocurrency-Analysis (Crypto-History)
Applying different regression models on Cryptocurrency data

The data is from kaggle at https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory which was created using the data published in coinmarketcap.com

We have chosen the Bitcoin and Ethereum Cryptocurrency for analysis due to their popularity
The data consists of the following:
1. Date
2. Opening price of the day
3. Closing price of the day
4. Highest price of the day
5. Lowest price of the day
6. Volume of transactions of the day
7. Market capitalization in USD

Models Used:
1. Linear Regression
2. K-NN Regression
3. SVM Regression
4. Decision Tree Regression
5. Gradient Boost Regression
6. Random Forest Regression

Here, we didn't treat the data as Time Series since there was an overall increasing trend and wasn't periodic or seasonal.
The highest price of the day was chosen to be predicted, and supervised learning models for regression were applied.
The goal was to **build a model that can describe the historical data**.
