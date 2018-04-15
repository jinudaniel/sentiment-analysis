# Sentiment analysis using LSTM and Keras
Sentiment Analysis is the process of determining whether a piece of writing is positive, negative or neutral. 
It’s also known as opinion mining, deriving the opinion or attitude of a speaker.
So in this repo we will perform a sentiment analysis on a series of tweets related to US Airlines. The data set can be obtained from
Kaggle using this [link](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)  
  
We will make use of Keras and LSTM to train this model as LSTM is very good in capturing long term dependencies of text data. In the
later part of this notebook I have made use of Pre Trained GloVe word embeddings instead of creating our own word embeddings
but this resulted in heavy overfitting on the training data. 
