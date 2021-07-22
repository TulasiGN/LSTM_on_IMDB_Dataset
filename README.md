# LSTM_on_IMDB_Dataset


Long short-term memory (LSTM) is an artificial recurrent neural network (RNN) architecture used in the field of deep learning. 
A common LSTM unit is composed of a cell, an input gate, an output gate and a forget gate. The cell remembers values over arbitrary time intervals and the three gates regulate the flow of information into and out of the cell.

LSTM networks are well-suited to classifying, processing and making predictions based on time series data, since there can be lags of unknown duration between important events in a time series. LSTMs were developed to deal with the vanishing gradient problem that can be encountered when training traditional RNNs. Relative insensitivity to gap length is an advantage of LSTM over RNNs

![image](https://user-images.githubusercontent.com/44425260/126625600-9b4f8596-ffd4-41b6-bcaa-b6387726c0b1.png)


In the Multilayered RNN,the actual problrm for us is Long term dependencies did not work well.In this case, we have a way to short circuit everything,becoz we have an indentity mapping here  in the architecture of LSTMjust like in RESTNEts.So, we are able to retain teh cell state.So,The the longTerm dependencies are possible here.we can skip few of the connections.

Now there is Mechanism,where I can impact something which is very faraway because of the possibilty of short Circuit Connection in the LSTM Architecture

-------------------------------------------------------------------

# IMDB DATASET

IMDB dataset having 50K movie reviews for natural language processing or Text analytics.
This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training and 25,000 for testing. So, predict the number of positive and negative reviews using either classification or deep learning algorithms.

