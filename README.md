# Introduction
* Sentiment Analysis is the process of categorizing opnionions expressed in a piece of text in order to determine whether the writer's attitude is positive, negative or neural.
* Dataset taken from [Kaggle](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

# About the dataset
* The dataset contains 4 columns viz id, entity, label and tweet.
* id represents the unique identifier assigned to each tweet.
* entity determines metadata and additional contextual information about contest posted on twitter. ([Source](https://developer.twitter.com/en/docs/twitter-api/v1/data-dictionary/object-model/entities#:~:text=Entities%20provide%20metadata%20and%20additional,Twitter%20polls%2C%20and%20attached%20media.))
* label determines whether the tweet is positive, negative or neutral.
* tweet contains actual tweets made by various users.

# Steps
* Exploratory Data Analysis
    * Null values
    * Proportions
    * Outliers
    * In-depth text analysis
* Preprocessing
    * Text normalization
    * Stop words
    * Stemming or lemmatization
    * Again EDA after normalization
        * Includes tfidf, frequencies, emogies etc.
* Model Training
* Hyperparameter Optimization