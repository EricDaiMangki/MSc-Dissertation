# MSc-Dissertation

This project focuses on using Natural Language Processing (NLP) and Large Language Models (LLMs) to analyze social media sentiment—specifically Twitter posts—and predict stock market returns. The study compares the performance of different models (e.g., TextBlob, VADER, and BERT) in predicting both the direction and magnitude of stock price movements based on sentiment polarity scores derived from tweet data.

The primary goal is to determine which models perform best in sentiment analysis within the financial context, Discovering on how fine-tuning the models can affect their predictive power. Additionally, we explore how the magnitude of sentiment (not just the direction) are linked to stock price returns and how good are each model in predicting the magnitute of return using their repective generated sentiemnt scores. 

## Features
Sentiment Analysis Models: Comparisons of NLP models (TextBlob, VADER) and LLMs (BERT) for sentiment classification.
Magnitude Prediction: Introduction of stock return classification based on sentiment intensity (small, medium, and large price movements).
Fine-Tuning: Analysis of how fine-tuning models can affect the performance for financial text data.

## Usage
1. Sentiment Analysis
You can apply various sentiment analysis models to your data:

TextBlob for basic lexicon-based sentiment scoring.
VADER for handling social media-specific sentiment features.
BERT for more advanced contextual understanding of sentiment.

2. Magnitude Prediction
A unique aspect of this project is the analysis of magnitude of stock returns. The stock returns are categorized into small, medium, and large movements, both positive and negative. These categories are used to evaluate the impact of sentiment on the scale of stock price changes.

3. Fine-Tuning
The project also allows for fine-tuning of NLP models like VADER and TextBlob to improve performance in financial contexts.

## Results
The project compares the performance of the models in predicting 1-day, 3-day, and 7-day stock returns, focusing on both direction and magnitude. The Random Forest classifier is used to assess the predictive power of each sentiment model.

Key findings include:

BERT outperformed both TextBlob and VADER in short-term predictions (1-day return).
Fine-tuning provided modest improvements but did not consistently outperform the non-tuned versions.
The analysis of return magnitude provides deeper insights into how sentiment affects not just the direction but also the scale of stock price movements.
