# Stock-Price-Prediction

I have used the concept of Recurrent Neural network here to predict how stock of Google is gonna behave in the future.

Here, timesteps of 2 months is used in time series forecasting approach.
The RNN used in this model consists of a LSTM with dropout & Regularization to remove bias and better results.

The final result of the model tells us how the stock is going to behave for next two months. The model captured most of the essence of the stock and it can be seen when we compare it with actual price. It didn't really captured surprising market fluctuations which can not be expected from any stock prediction model as well as market runs on so many parameters which is hard to capture in a model with help of only data.
