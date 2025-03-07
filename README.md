# Twitter-sentimental-analysis

This project performs sentiment analysis on Twitter data using an LSTM model. The model classifies tweets into three sentiment categories: positive, negative, or neutral based on the content of the tweet.

Technologies Used
Python (Programming Language)
TensorFlow / Keras (Deep Learning Framework)
Pandas (Data Handling)
NumPy (Numerical Operations)
Matplotlib (Data Visualization)
WordCloud (Visualizing frequent words)

## Usage
Open the twitter_sentiment_analysis.ipynb notebook.
Load the dataset containing tweets.
Preprocess the data using the following techniques:
Tokenization: The text is split into individual words (tokens), which are used as input for the model.

Stopword Removal: Words like "the", "is", and "and" are removed because they do not provide valuable information for sentiment analysis.
Lemmatization: Words are reduced to their base form (e.g., "running" becomes "run") to simplify the dataset and standardize the input.
Word Cloud: A visual representation of the most frequent words in the dataset, which helps to understand the key terms and themes of the tweets.
Train the LSTM model on the preprocessed data.
Use the trained model to predict the sentiment of new tweets, classifying them as positive, negative, or neutral.

## Dataset
This project uses a dataset of tweets labeled with sentiment categories. You can use a publicly available dataset such as Sentiment140, or upload your own set of tweets for analysis.
