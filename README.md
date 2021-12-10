# StockPrice-Prediction-Using-Pytorch-Neural-Network
 End-to-End data science lifecycle of developing a predictive model for stock price movements with Alpha Vantage APIs and a powerful machine learning algorithm called Long Short-Term Memory (LSTM). Key concepts of machine learning / deep learning are shown and built a fully functional predictive model for the stock market, all in a single Python file.
 
 # LSTM Networks
 Long Short Term Memory networks – usually just called “LSTMs” – are a special kind of RNN, capable of learning long-term dependencies. They were introduced by [Hochreiter & Schmidhuber (1997)](http://www.bioinf.jku.at/publications/older/2604.pdf), and were refined and popularized by many people in following work.1 They work tremendously well on a large variety of problems, and are now widely used.

LSTMs are explicitly designed to avoid the long-term dependency problem. Remembering information for long periods of time is practically their default behavior, not something they struggle to learn!

All recurrent neural networks have the form of a chain of repeating modules of neural network. In standard RNNs, this repeating module will have a very simple structure, such as a single tanh layer.

![](https://github.com/Abhishek-Aditya-bs/StockPrice-Prediction-Using-Pytorch-Neural-Network/blob/main/LSTM-pic.png)

<p align='center'> The repeating module in a standard RNN contains a single layer.</p>

LSTMs also have this chain like structure, but the repeating module has a different structure. Instead of having a single neural network layer, there are four, interacting in a very special way.

![](https://github.com/Abhishek-Aditya-bs/StockPrice-Prediction-Using-Pytorch-Neural-Network/blob/main/LSTM-chain.png)

<p align='center'> The repeating module in an LSTM contains four interacting layers.</p>

![](https://github.com/Abhishek-Aditya-bs/StockPrice-Prediction-Using-Pytorch-Neural-Network/blob/main/LSTM-notation.png)

In the above diagram, each line carries an entire vector, from the output of one node to the inputs of others. The pink circles represent pointwise operations, like vector addition, while the yellow boxes are learned neural network layers. Lines merging denote concatenation, while a line forking denote its content being copied and the copies going to different locations.


# Output Screenshots

<p align='center'> Comparison of Predicted Prices to actual Prices </p>

![](https://github.com/Abhishek-Aditya-bs/StockPrice-Prediction-Using-Pytorch-Neural-Network/blob/main/output-1.png)

<p align='center'> Zoomed in to examine predicted price on validation data portion </p>

![](https://github.com/Abhishek-Aditya-bs/StockPrice-Prediction-Using-Pytorch-Neural-Network/blob/main/output-2.png)



