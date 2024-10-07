# Sentiment Analysis on Amazon Reviews using NLTK's Vader Sentiment Scoring
A sentiment analysis project utilizing NLTK’s Vader Sentiment Scoring to classify customer reviews as positive, neutral, or negative. The project includes data preprocessing scripts, detailed Jupyter notebooks, and visualization examples.

## Project Overview :
This project leverages NLTK's Vader Sentiment Scoring to perform sentiment analysis on customer reviews. The goal is to classify each review as positive, negative, or neutral, providing valuable insights into customer opinions. The tool is particularly well-suited for analyzing short texts, such as social media posts or reviews, due to its ability to detect contextual polarity.

## How Vader Sentiment Scoring Works
The Vader (Valence Aware Dictionary and sEntiment Reasoner) algorithm calculates sentiment scores based on the presence of positive and negative words, as well as the intensity of these words. It also considers punctuation, capitalization, and degree modifiers (e.g., words like "very" or "extremely") to improve accuracy.

The resulting score ranges from:

Positive (Compound > 0.05)
Neutral (Compound between -0.05 and 0.05)
Negative (Compound < -0.05)

## Repository Contents:
notebooks/: Jupyter notebooks containing step-by-step instructions on how to preprocess data, implement Vader Sentiment Scoring, and visualize results.
data/: Sample datasets used in the analysis. These include both raw and preprocessed data.
scripts/: Python scripts for preprocessing data, performing sentiment analysis, and generating reports.
