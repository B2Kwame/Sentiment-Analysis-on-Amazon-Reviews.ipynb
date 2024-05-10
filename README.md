# Sentiment-Analysis-on-Amazon-Reviews.ipynb
# Sentiment analysis on Amazon Reviews using Naive Bayes Classifier 

# Overview
This project leverages the power of natural language processing (NLP) to analyze the sentiment of product reviews. By using the TextBlob library, which defaults to the Naive Bayes classifier, we assess whether the sentiments expressed in the reviews are positive, negative, or neutral based on the polarity score.

# Data Workflow
The process begins by converting data from JSON format to CSV, followed by several preprocessing steps including tokenization, removal of stopwords and punctuation, lemmatization, and converting text to lowercase. This cleaned data is then fed into our sentiment analysis pipeline.

# Sentiment Analysis
The sentiment analysis is conducted through the following steps:
# TextBlob Conversion
The cleaned review text is converted into a TextBlob object to utilize NLP tools.
# Polarity Calculation
TextBlob computes the polarity of the text, which ranges from -1 (very negative) to +1 (very positive).
Label Assignment: Based on the polarity score, reviews are categorized as:

# Positive
Polarity > 0
# Negative 
Polarity < 0
# Neutral
Polarity = 0

# Visualization
Various visualizations are implemented to better understand the distribution and frequency of sentiments among the reviews, using libraries such as Matplotlib and Seaborn.

# Conclusion
This project provides a straightforward method for sentiment analysis on product reviews, offering insights that could be valuable for businesses looking to understand consumer sentiment towards their products.
