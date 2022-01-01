# AI Stock Price Predictor
Used a Long Short-Term Memory (LTSM) Artificial Recurrent Neural Network (RNN) model to predict future stock prices.



Below is a short visual representation of what the model does:


Graph of SPXL (3x Leveraged S&P500):

![image](https://user-images.githubusercontent.com/82794849/147861274-8d4cb3fe-31ed-4ecc-a6be-fa6df47968ca.png)

Graph showing training of LTSM RNN model on SPXL:

![image](https://user-images.githubusercontent.com/82794849/147861300-6107d911-03bc-4254-976c-50b83707cbc7.png)

Graph showing predicted 30 day future prices extended out from current graph of SPXL:

![image](https://user-images.githubusercontent.com/82794849/147861315-2f6d9949-56b8-4c78-bd62-e83a0b7f2697.png)




Assumptions that this model takes:
1. Previous prices (and patterns) are an indication of future prices
2. Overall market conditions have not changed

Ways to improve this model:
1. Incorporate factors outside of market price data such as leading economic indicators
2. Backtest the model in specific segments with similar market conditions
