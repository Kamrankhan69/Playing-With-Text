# Playing-With-Text
Used Sentiment140 dataset (https://www.kaggle.com/datasets/kazanova/sentiment140) and perform following tasks, 

load the dataset and display number of samples for each class label (0=neg, 1=neutral, 4=pos)
clean it to remove stop-words and punctuation
split dataset in train and test with 30-70 ratio, ensure stratified split
train following models while validating each of these on 20% of the training data, 
RNN with an embedding layer and two hidden layers (64, 32) to learn word embedding from the data, keeping max feature size = 10000 and max length of each tweet 140 words
Check the impact of adding an additional layer of 128 in first task
Repeat 1 and 2, this time use GloVe with 100-dim instead of learning word-embedding through embedding layer
Repeat 3, this time use GloVe-twitter instead of GloVe
Repeat 3, replace GloVe with FastText
Repeat 1-5, replace RNN with LSTM
