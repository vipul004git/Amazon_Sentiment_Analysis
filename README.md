# Sentiment Analysis of Amazon Reviews
## Overview
E-commerce has revolutionized the way consumers shop, with online reviews playing a crucial role in decision-making. This project focuses on analyzing sentiments in Amazon product reviews using machine learning techniques. By classifying reviews as positive, negative, or neutral, we aim to provide valuable insights for both consumers and businesses.

## Dataset
We used a large-scale Amazon dataset from Kaggle, which includes attributes like reviewer ID, product ID, reviewer name, review text, overall rating, review summary, and review timestamp. The ratings range from 1 to 5, representing satisfaction levels.

## Methodology
### Data Preprocessing: 
Tokenization, text cleaning, and stopword removal were performed to prepare the text data for analysis.
### Feature Engineering: 
We used Bag of Words and TF-IDF techniques to extract features from the text data.
### Data Balancing: 
Due to class imbalance, we used SMOTE to oversample the minority classes (negative and neutral reviews).
### Model Selection: 
We trained two models - Naive Bayes and Logistic Regression - using the TF-IDF features and selected the best performing model based on cross-validation.
## Results
### Naive Bayes Model:
Accuracy - 78.37%, F1-score - 0.79
### Logistic Regression Model: 
Accuracy - 79.45%, F1-score - 0.73
## Conclusion
This project demonstrates the effectiveness of machine learning in sentiment analysis of Amazon reviews. The models can help consumers make informed decisions and provide businesses with insights to improve their products and services.
