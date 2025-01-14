# Sentiment-Analysis-of-Customer-Reviews
Project Overview:

This project aims to perform Natural Language Processing (NLP) and Sentiment Analysis on a dataset of customer reviews to extract insights such as word frequency and the overall sentiment of the reviews. The analysis provides an overview of customer opinions based on review text and ratings, which can be useful for businesses to gauge customer satisfaction.

Objectives:

Text Preprocessing:

Remove stopwords, punctuation, and special characters.
Tokenize and lemmatize the review text to standardize the words.

Exploratory Data Analysis (EDA):

Identify and visualize the most frequent words from the reviews using bar charts and word clouds.

Sentiment Analysis:

Perform sentiment analysis using the VADER Sentiment Analyzer (from the NLTK library) to classify reviews as Positive, Neutral, or Negative.

Visualizations:

Visualize sentiment distribution and top frequent words.

Dataset:

The dataset used in this project contains customer reviews with text data and review ratings (stars) of products. The columns in the dataset include:

Id: Unique identifier for the review.

ProductId: Product identifier.

UserId: User who posted the review.

ProfileName: Profile name of the user.

HelpfulnessNumerator: Number of helpful votes.

HelpfulnessDenominator: Total number of votes.

Score: Rating of the product (1 to 5).

Time: Timestamp of the review.

Summary: Summary of the review.

Text: The detailed review text.

Technologies Used:

Pandas: Data manipulation and analysis.

NumPy: Numerical operations.

Matplotlib & Seaborn: Data visualization.

NLTK (Natural Language Toolkit): Text processing tasks such as tokenization, lemmatization, and stopword removal.

VADER Sentiment Analyzer: For performing sentiment analysis.

How to Run the Project:


Jupyter Notebook File:

[SENTIMENT ANALYSIS.ipynb]: The Jupyter notebook contains all the steps and analysis, including:

Loading and exploring the dataset.

Preprocessing the review text.

Performing sentiment analysis.

Generating visualizations such as bar charts.

Output and Results:

Sentiment Distribution: A bar chart showing the distribution of Positive, Neutral, and Negative reviews.

Word Frequency Analysis: A bar chart showing the top 10 most frequent words across all reviews.

Sentiment Summary: A percentage breakdown of the sentiment classification:

Positive: 91.43%

Negative: 6.69%

Neutral: 1.88%

Conclusion:

This project provides an analysis of customer reviews through text preprocessing, sentiment analysis, and visualizations. By understanding the sentiment of reviews and identifying common words, businesses can improve customer experience, product quality, and marketing strategies.

