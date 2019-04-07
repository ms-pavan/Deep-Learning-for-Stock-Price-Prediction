# Deep Learning for Stock Price Prediction


Deep learning system to predict stock prices of next day (one step time series forecast) and also for a specific period of time (multi-step time series forecast). Stock traders analyze various patterns in the stock market in order to make their investment decisions. Using this system, stock traders can automate their process of decision making. 

Predicting Stock prices can be achieved using deep learning models like LSTM (Long Short-Term Memory Networks), GRU (Gated Recurrent Unit), CNN (Convolutional Neural Network) plus LSTM models because of their ability to remember past information. We solved this project using two approaches.
1) One step prediction takes the test set until the previous day and predicts the next price.
2) Multistep prediction starts with the first window in the test set, predicts next price, then pops out the oldest price in the window, appends the predicted price and predicts the next price on this new window for a specified period.
