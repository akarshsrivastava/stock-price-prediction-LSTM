# stock-price-prediction-LSTM

Many financial firms, hedge funds and retail investors use financial models to understand the market trend so as to make informed decision which could provide profitable outcomes. 
These firms, hedge funds and retail investors use historical data of the companies in the form stock prices, balance sheets, performance reports for making their decisions
With more and more advancement in technology that is supported by computational capabilities, machine learning and deep learning techniques are proving to be very useful.

The analysts try to analyze the available data in order to make informed guesses because one can never be 100% accurate in this case. Can machine learning and deep learning algorithms/techniques help in predicting stock prices ? To state a fact, around 70% of all orders on Wall Street are now placed by software, we're now living in the age of the algorithm. 

In my project, I have explored one such technique, Long-Short Term Memory (LSTM) Neural Network algorithm, to predict stock prices. For data with timeframes recurrent neural networks (RNNs) come in handy but recent researches have shown that LSTM, networks are the most popular and useful variants of RNNs.

Dataset:
For this project, I have used historical stock price data of ITC stock(listed on India's National Stock Exchange) from January 1, 2014 to October 11, 2020. The dataset is acquired from Yahoo Finance website. 

This dataset provides the following important information for each trading session:
1. Open	Price 
2. High Price	
3. Low Price	
4. Close Price	
5. Volume traded

For my project I have only used the Closs price if each day. I have approach this problem as a time series one, where I have continuous price data from which I intend to predict future close price of the stock for next 30 days.

# Software and Libraries
For this project, I have used the following software and Python libraries:
1.Python 2.7
2. NumPy
3. pandas
4. Matplotlib
5. Keras
6. Tensor-flow
7. Jupyter Notebook
