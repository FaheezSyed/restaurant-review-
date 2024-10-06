# Restaurant Review Sentiment Analysis

## Overview
This project implements a sentiment analysis model to classify restaurant reviews as positive or negative.

## Requirements
- Python 3.7+
- pandas
- scikit-learn
- nltk

## Installation
```
pip install pandas scikit-learn nltk
```

## Usage

### 1. Data Preparation
Place your restaurant review dataset in a TSV file named `Restaurant_Reviews.tsv` with columns:
- `Review`: The text of the review
- `Liked`: The sentiment label (1 for positive, 0 for negative)

### 2. Preprocessing
- Remove punctuation and special characters
- Convert text to lowercase
- Remove stopwords
- Perform stemming

### 3. Model Training
Train the sentiment analysis model:
- Split the data into training and testing sets
- Vectorize the text using CountVectorizer
- Train a Gaussian naive bayes model
- Train a Logistic Regression model
- Train a Random Forest Classifier model
- Save the trained model as `restaurant_review.pkl`

  
## Future Improvements
- Experiment with different machine learning algorithms
- Implement deep learning models (e.g., LSTM, BERT)
- Collect more diverse training data
