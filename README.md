# lstm-nifty-prediction
* Stock Price Prediction And Forecasting Using Stacked LSTM- Deep Learning
* Disclaimer: This is just a demonstration of using LSTM in predicting the future price of a stock market instrument and is a learning experience in application of data science in doing so.
* Do not place your trades only based on this demonstration.
* I am not responsible for any loses you might incur in doing so.
* Market trends are determined by many factors many of which are beyond the scope of this exercise. So do responsible investing/ trading  
## Project Overview

Investment firms, hedge funds and even individuals have been using financial models to better understand market behaviour and make profitable investments and trades. A wealth of information is available in the form of historical stock prices and company performance data, suitable for machine learning algorithms to process.

Can we actually predict stock prices with machine learning? Investors make educated guesses by analysing data. They'll read the news, study the company history, industry trends and other lots of data points that go into making a prediction. The prevailing theories is that stock prices are totally random and unpredictable but that raises the question why top firms like Morgan Stanley and Citigroup hire quantitative analysts to build predictive models. We have this idea of a trading floor being filled with adrenaline infuse men with loose ties running around yelling something into a phone but these days they're more likely to see rows of machine learning experts quietly sitting in front of computer screens. In fact about 70% of all orders on Wall Street are now placed by software, we're now living in the age of the algorithm.

This project utilizes Deep Learning models, Long-Short Term Memory (LSTM) Neural Network algorithm, to predict stock prices. For data with timeframes recurrent neural networks (RNNs) come in handy but recent researches have shown that LSTM, networks are the most popular and useful variants of RNNs. 

I have used Keras to build a LSTM to predict stock prices using historical closing price and trading volume and visualize both the predicted price values over time and the optimal parameters for the model.

Raw chart as on 29/12/2021

![Stock Price Predictor]( https://github.com/bala-stack/lstm-nifty-prediction/blob/main/1.png)




Forecasted chart as on 29/12/2021 + 30 days

![Stock Price Predictor]( https://github.com/bala-stack/lstm-nifty-prediction/blob/main/2.png)

![Stock Price Predictor]( https://github.com/bala-stack/lstm-nifty-prediction/blob/main/3.png)

![Stock Price Predictor]( https://github.com/bala-stack/lstm-nifty-prediction/blob/main/4.png)

Things I have learnt by completing this project:
* How to apply deep learning techniques: Long Short Term Memory Neural Network algorithms.
* How to use keras-tensorflow library.
* How to collect and pre-process given data.
* How to analyse model's performance.
* How to optimise Long Short Term Memory Neural Network algorithm, to ensure increase in positive results.

## Software and Libraries
This project uses the following software and Python libraries:

* [Python 2.7](https://www.python.org/download/releases/2.7/)
* [NumPy](http://www.numpy.org/)
* [pandas](http://pandas.pydata.org/)
* [Keras](https://keras.io/)
* [Tensor-flow](https://www.tensorflow.org)
* [Jupyter Notebook](http://ipython.org/notebook.html)

