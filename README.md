# Sentiment Analysis of Covid-19 Tweets

The aim of this project is to determine the inclination of people by their tweets on Covid-19. The program classifies only English tweets.

## Project Development Steps

- Fetch tweets using covid-19 and related key words using twitterscraper ✅
- Preprocess data (NLTK and PorterStemmer) ✅
- Label positive, negative and neutral sentiments of tweets (SentimentIntensityAnalyzer) ✅
- Visualize word occurences (WordCloud, Seaborn, Matplotlib) ✅
- Apply Naive Bayes Classifier algorithm - pending

## Preprocessing Steps

- Cleansing
- Remove https from tweets
- Remove pic tags of tweets
- Remove special characters
- Remove numbers
- Remove English stopwords
- Tokenize
- Transform to lowercase
- Stem