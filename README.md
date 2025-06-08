# Sentiment-Analysis

Sentiment Classification Project
Project Overview
This project focuses on sentiment classification of text data, aiming to determine whether a given statement expresses a positive or negative sentiment. Sentiment analysis is a fundamental task in Natural Language Processing (NLP) with applications in product reviews, social media monitoring, customer feedback systems, and more.
The project leverages a labeled dataset of text samples annotated as either positive or negative, enabling a balanced binary classification task. Two models are implemented: a traditional machine learning approach and a deep learning approach, evaluated using standard NLP metrics.
Dataset Description

Source: IMDB 50K Movie Reviews Dataset( https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
Class Distribution: Balanced
25,000 positive reviews
25,000 negative reviews


Columns:
review: Text of the movie review
sentiment: Label (positive or negative)



Models
Two models are implemented for sentiment classification:

Machine Learning:
Model: Logistic Regression
Feature Extraction: TF-IDF


Deep Learning:
Model: Long Short-Term Memory (LSTM) network
Feature Representation: Word Embeddings



Evaluation Metrics
The performance of both models is assessed using the following metrics:

Accuracy: Proportion of correctly classified reviews
F1-Score: Harmonic mean of precision and recall
Precision: Proportion of true positive predictions among all positive predictions
Recall: Proportion of true positives identified correctly
ROC-AUC: Area under the Receiver Operating Characteristic curve, measuring model discrimination


Evaluation:

Results (accuracy, F1-score, etc.) will be printed and saved in the notebooks/analysis.ipynb.
