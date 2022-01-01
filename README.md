# LSTM_Stock_Prediction
LSTM model to predict future stock prices

Used a Long Short-Term Memory (LTSM) Artificial Recurrent Neural Network (RNN) model to predict future stock prices.


Graph of SPXL (3x Leveraged S&P500):
![image](https://user-images.githubusercontent.com/82794849/147861274-8d4cb3fe-31ed-4ecc-a6be-fa6df47968ca.png)

Graph showing training of LTSM RNN model:

Graph showing predicted 30 day future prices:



Assumptions that this model takes:
1. Previous prices (and patterns) are an indication of future prices
2. Overall market conditions have not changed

Ways to improve this model:
1. Incorporate factors outside of market price data such as leading economic indicators
2. Backtest the model in specific segments with similar market conditions
