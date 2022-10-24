# Sentiment Analysis French Tweets
NLP sentiment analysis on french tweets

## Introduction

The task in this project is to develop a machine learning model to classify tweets in french language. One of the challenges here is to deal with particularities of the french language which is not part of the default setting of most ML libraries.

The dataset consists of text from tweets in french and integer where 1 represents positive sentiment and 0 represents negative sentiment. The dataset file contains around 1.5 millions tweets. In this project the dataset is reduced to 400 000 samples to deal with the RAM limitations. 

## Predictive models

The RNN acitecture choosen for the model is the many-to-one architecture

![Many-to-One](/data/many-to-one.JPG)


### Single LSTM Neural Network

![Single Model Image 1](/data/tweets_single_1.JPG)
![Single Model Image 2](/data/tweets_single_2.JPG)

### Bidirectional LSTM Neural Network

![Bidirect Model Image 1](/data/tweets_bidirect_1.JPG)
![Bidirect Model Image 2](/data/tweets_bidirect_2.JPG)

## Results

## Conclusion

