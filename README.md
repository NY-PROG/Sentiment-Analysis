# Sentiment Analysis for Restaurant Reviews
This project aims to build a binary classification model using Naive Bayes classifier to automatically classify customer reviews from Facebook as either positive or negative. 
By analyzing negative reviews, ABC Restaurant can identify areas for improvement and enhance service quality.

Goals
---
a) Automatically classify reviews into positive (1) and negative (0) categories
b) Analyze negative reviews to improve restaurant service quality

Dataset
---
Historical Reviews (900 samples):
Pre-labeled English customer reviews (text only)
Labels:
1: Positive review
0: Negative review
80% training data/20% testing data

Recent Reviews (100 samples):
Unlabeled English customer reviews (text only) for prediction

Features of the Project
---
Data Preprocessing:
    
Removing punctuation and numbers: All non-text characters will be removed
Converting to lowercase: All text will be converted to lowercase to ensure uniformity
Removing stop words: Common words (e.g., "the," "is," "and") that do not add meaningful context to sentiment analysis will be removed
Stemming: Words will be reduced to their root forms (e.g., "running" → "run")
    
Model Training: Uses Naive Bayes classifier to classify reviews as "positive" or "negative"
Performance Metrics: Assesses model accuracy
Export Predictions: Saves model predictions to .csv or .xlsx formats

Tools and Libraries
---
pandas, numpy, scikit-learn, NLTK, pickle


Output
---
Model Accuracy: 72.8%
