# Predicting-cryptocurrency-prices-using-ARIMA
In this study, we build an ARIMA(4,1,0) model to forecast short-term prices for Bitcoin and a portfolio. It shows an accuracy of 98% for Bitcoin predictions and of 97% for Bitcoin portfolio (cryptocurrencies with similar price trends as Bitcoin) predictions. These findings indicate a great fitting of the model for short-term predictions.

The project mainly focuses on price forecasting of cryptocurrency using the ARIMA model. We have divided our project into 4 parts:
1. Cryptocurrency market analysis: exploratory data analysis with multiple features in our cryptocurrency market data
2. Bitcoin price prediction using ARIMA: building an ARIMA model based on Bitcoin price history and using it to forecast Bitcoin prices
3. Creating weighted portfolio: grouping various cryptocurrencies with similar price trends, de- termining their weights in the portfolio based on their market prices, and creating a portfolio for an initial investment, with equally dividing it among the portfolio members
4. Portfolio analysis and modelling: analyzing the changes in the overall price change, after an initial investment, based on the price changes of the cryptocurrencies in it and modelling this data for portfolio price prediction.

For this project, we refer to various past works done on this topic or related topics and use the histor- ical daily market price data for all cryptocurrencies, which is imported from Kaggle. We use an ARIMA model on our data to make and graph them to ana- lyze the accuracy of the model. We also use the MAPE score to mathematically determine the accuracy of the model and determine if it fits well with the data and if it can be used for forecasting the prices
