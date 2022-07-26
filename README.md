Introduction- 
Historical stock market data for current S&P 500 companies, from 2014-2017. Each record represents a single day of trading, and includes the ticker name, volume, high, low, open and close prices.

Business Problem-
Prediction of stock price index movement is regarded as a challenging task of financial time series prediction. An accurate prediction of stock price movement may yield profits for investors. Due to the complexity of stock market data, development of efficient models for predicting is very difficult.
We are trying to predict the stock prices for next few days. This will help the investors or traders forecast the movement of the market. This will become base to know right time to invest or exit the positions and yield profit.

ML formulation of the business problem-
This will be regression problem as we are prediction the prices i.e. integer values. 
Stock price data are time sensitive. That is, the stock price at the current time point is closely related to that at short-time points rather than overdue time points. The data is a series data, we will split the data into train and test. For each stock there are 1007 values that means roughly the test data will be of 200 points i.e. we will be predicting the price for 200 days. 

Business constraints-
The cost of a mis-classification can be very high.
No strict latency concerns, as we are predicting the prices for nest few days and for next few minutes

Dataset analysis-
Data Set named (Historical stock market data for current S&P 500 companies, from 2014-2017) on kaggle. The data set contains data from 2014 to 2017 of S & P 500. The Standard and Poor's 500, or simply the S&P 500, is a stock market index tracking the performance of 500 large companies listed on stock exchanges in the United States. It is one of the most commonly followed equity indices. As of December 31, 2020, more than $5.4 trillion was invested in assets tied to the performance of the index. There are 505 unique values i.e. 505 total stocks that are listed on United States stock market.

Performance Metric-
RMSE
