# Sentiment Analysis French Tweets
NLP sentiment analysis on french tweets

## Introduction

The task in this project is to develop a machine learning model to classify tweets in french language. One of the challenges here is to deal with particularities of the french language which is not part of the default setting of most ML libraries.

The dataset consists of text from tweets in french and integer where 1 represents positive sentiment and 0 represents negative sentiment. The dataset file contains around 1.5 millions tweets. In this project the dataset is reduced to 400 000 samples to deal with the RAM limitations. 

## Predictive models

The RNN architecture choosen for the model is the many-to-one architecture

![Many-to-One](/data/many-to-one.jpg)


### Single LSTM Neural Network

![Single Model Image 1](/data/tweets_single_1.JPG)
![Single Model Image 2](/data/tweets_single_2.JPG)

### Bidirectional LSTM Neural Network

![Bidirect Model Image 1](/data/tweets_bidirect_1.JPG)
![Bidirect Model Image 2](/data/tweets_bidirect_2.JPG)

## Results

| dataset      | accuracy(single LSTM) | accuracy(bidirectional LSTM) |
| -------------| ----------------------|------------------------------|
| train        | 77.58%                |78.28%                        |
| validation   | 76.55%                |76.54%                        |
| test         | 76.30%                |76.21%                        |

## Conclusion

The single LSTM neural network works slightly better than the bidirectional LSTM NN. The final model (single LSTM) generalizes good as the accuracy on train set is around 77.7% and the accurace on test set is around 76.5%. There is no overfitting. However this score is not very high. An improvement could be achieved using attention model.


