# Sentiment Analysis on IMDB Movie Reviews
This project analyzes sentiments (positive or negative) in the IMDB dataset of 50,000 movie reviews using Natural Language Processing (NLP) techniques. The goal is to preprocess the text data, visualize key patterns, and extract insights through feature engineering and machine learning.

Dataset
The dataset used is the IMDB Dataset of 50K Movie Reviews, which contains labeled reviews as "positive" or "negative".

Project Workflow
Data Cleaning:

Removed duplicates and irrelevant characters (HTML tags, URLs).
Expanded contractions (e.g., "can't" to "cannot").
Corrected spelling mistakes.
Text Preprocessing:

Tokenized text into words.
Removed stopwords and punctuation.
Engineered features such as character and word lengths.
Feature Engineering:

Created a Bag of Words (BoW) feature matrix using unigrams, bigrams, and trigrams.
Applied PCA for dimensionality reduction.
Visualization:

Generated word clouds for positive and negative reviews.
Analyzed distributions of review lengths and their relationships with sentiments.
Technologies Used
Languages: Python
Libraries: Pandas, NumPy, NLTK, TextBlob, Scikit-learn, Seaborn, Matplotlib, WordCloud
Insights
Positive reviews often include longer sentences with descriptive terms.
Negative reviews are shorter and highlight dissatisfaction directly.
N-grams analysis revealed common word patterns specific to each sentiment.
