# Sentiment-Analysis
Sentiment Analysis on Amazon Reviews
This repository contains code for performing sentiment analysis on Amazon reviews using different models.

Overview
The main goal of this project is to analyze the sentiment of Amazon reviews using two different models: VADER and ROBERTa.

Data
The dataset used for this analysis is an Amazon reviews dataset, which can be downloaded from the following link:

https://www.kaggle.com/code/benroshan/sentiment-analysis-amazon-reviews

Models
1. VADER Model
VADER (Valence Aware Dictionary and sEntiment Reasoner) is a rule-based sentiment analysis tool specifically designed for analyzing sentiments expressed in text. In this project, VADER is used to calculate sentiment scores for the review text.

2. ROBERTa Model
ROBERTa (A Robustly Optimized BERT Approach) is a transformer-based model designed for natural language understanding tasks, including sentiment analysis. We utilize a pre-trained ROBERTa model to perform sentiment analysis on the review text.

Code Structure
sentiment_analysis.py: Python script containing the code for sentiment analysis using VADER and ROBERTa models.
Results
The sentiment analysis results are displayed in the form of bar charts, showing the distribution of positive and negative sentiments across the reviews.

