# Deep-Learning-Models-with-Technical-Indicators-for-Stock-Price-Forecasting
Forecasting prices of stock market has always been a challenging problem for many researchers \& business analysts. The rate of investment \& the business opportunities in the Stock market may increase if some efficient algorithm could be invented or devised to predict short term price of some individual stock. In this project implementation of Recurrent Neural Network (RNN) and its variannts is being done for predicting the closing price of the succeeding day. 
The aim of this project is that to examine feasibility \& performance of our RNN based models in forecasting stock prices.

# Recurrent Neural Network
RNN works on the principle of saving the output of a particular layer and feeding this back to the input in order to predict the output of the layer.
An RNN can handle sequential data, accepting the current input data, and previously received inputs. RNNs can memorize previous inputs due to their internal memory.
![Fully_connected_Recurrent_Neural_Network](https://user-images.githubusercontent.com/88109927/180086935-32d55d7d-65ae-4abb-b940-091947f311fb.gif)

# Long Short Term Memory (LSTM)

LSTM-based model is just an extension of vanilla RNN, which addresses a solution for the vanishing
gradient problem.
A typical LSTM architecture consists of three gates as discussed below:
```
Forget Gate
Input Gate
Outout Gate
```
![lstm](https://user-images.githubusercontent.com/88109927/180088034-3dfe6fe4-46bf-4f98-8d4e-7ebda0e159a4.png)

# Bi-Directional LSTM
Bi-LSTM or simply bidirectional LSTM is a successor of the above
described LSTM model in which two LSTMs are being applied
to the input data s. In the first phase, an LSTM is fed upon the input data sequence (i.e., the forward layer). And in the second
phase, we fed the reverse form of the given input data sequence to the
LSTM model (i.e., the backward layer).


![BiLSTM](https://user-images.githubusercontent.com/88109927/180088485-ddad4fee-3732-4dc7-9b67-8f541ab24f56.png)



