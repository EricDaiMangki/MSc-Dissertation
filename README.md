# MSc-Dissertation

This project focuses on using Natural Language Processing (NLP) and Large Language Models (LLMs) to analyze social media sentiment—specifically Twitter posts—and predict stock market returns. The study compares the performance of different models (e.g., TextBlob, VADER, and BERT) in predicting both the direction and magnitude of stock price movements based on sentiment polarity scores derived from tweet data.

The primary goal is to determine which models perform best in sentiment analysis within the financial context, Discovering on how fine-tuning the models can affect their predictive power. Additionally, we explore how the magnitude of sentiment (not just the direction) are linked to stock price returns and how good are each model in predicting the magnitute of return using their repective generated sentiemnt scores. 

## Features
Sentiment Analysis Models: Comparisons of NLP models (TextBlob, VADER) and LLMs (BERT) for sentiment classification.
Magnitude Prediction: Introduction of stock return classification based on sentiment intensity (small, medium, and large price movements).
Fine-Tuning: Analysis of how fine-tuning models can affect the performance for financial text data.


├── data/                      # Folder for storing tweet and stock return data
├── notebooks/                 # Jupyter notebooks with code and analysis
├── README.md                  # Project documentation (this file)
