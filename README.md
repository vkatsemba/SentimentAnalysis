# SentimentAnalysis

This is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the twitter api . The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment .

It contains the following 6 fields:

target: the polarity of the tweet (0 = negative, 4 = positive)
ids: The id of the tweet ( 2087)
date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
flag: The query (lyx). If there is no query, then this value is NO_QUERY.
user: the user that tweeted (robotickilldozr)
text: the text of the tweet (Lyx is cool)

In the Jupyter Notebook, we perform exploratory anaylysis of tweets, with WordClouds, preprocess the tweets, perform count vectorization and run several classification models and evaluate them.

https://www.kaggle.com/kazanova/sentiment140

IMDB dataset having 50K movie reviews for natural language processing or Text analytics.
This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training and 25,000 for testing. So, predict the number of positive and negative reviews using either classification or deep learning algorithms.

In the Jupyter Notebook, we perform exploratory anaylysis of tweets, with WordClouds, preprocess the tweets, perform tfidf vectorization and porter stemming before running a Logistic Regression classification model with tuned hyperparameters and evaluate it.

http://ai.stanford.edu/~amaas/data/sentiment/
