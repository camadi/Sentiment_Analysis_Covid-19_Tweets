# Building Sentiment Analysis Model and prediction of Covid-19 Tweets

The project aims at building a sentiment analysis model using `Sentiment140` data set and predict the sentiment of tweets. The model was applied in predicting specifically Covid 19 tweets, and results compared to prebuilt SentimentIntensityAnalyzer model which appears to have wrongly classified the sentiment of some Covid 19 tweets. The model classifies only English tweets.

Some methods used include:

- Word2Vec
- LSTM
- cld3
- sklearn
- nltk
- keras
- WordNetLemmatizer
- twitterscraper etc.

## Project Development Steps

- Train using `Sentiment140` data set using Word2Vec ✅
- Testing and plotting results as well as classification report ✅
- Fetch tweets using covid-19 and related key words using twitterscraper ✅
- Preprocess data (nltk and WordNetLemmatizer) ✅
- Label positive, negative and neutral sentiments of tweets  ✅
- Visualize word occurences (WordCloud, Seaborn, Matplotlib) ✅
- Predict sentiments using models trained on `Sentiment140` data set ✅
- Compare trained result with SentimentIntensityAnalyzer sentiments ✅
- Apply Naive Bayes and logistic regression Classifier algorithm - pending

## Preprocessing Steps

- Cleansing
- Remove https from tweets
- Remove pic tags of tweets
- Remove special characters
- Remove English stopwords
- Tokenize
- Transform to lowercase
- Lemmatize
- Remove handles and hashes