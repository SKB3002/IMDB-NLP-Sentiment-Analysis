# IMDb Movie Review Sentiment Analysis

This project builds a machine learning system to classify IMDb movie reviews as **positive** or **negative** using Natural Language Processing (NLP) techniques.

## Overview
- Binary sentiment classification on movie reviews
- Focus on interpretability and strong baseline models
- End-to-end pipeline from text preprocessing to deployment-ready inference

## Approach
- Text preprocessing: cleaning, tokenization, lemmatization
- Feature extraction: Bag of Words, TF-IDF, Word2Vec
- Models evaluated: Logistic Regression, Naive Bayes, SVM
- Evaluation metrics: Accuracy, Precision, Recall, F1-score

## Results
- **Best model:** Logistic Regression with TF-IDF
- Achieved strong performance with high interpretability
- Model learned sentiment primarily from opinion-bearing adjectives rather than topic words

## Key Insights
- TF-IDF outperformed dense embeddings for sentiment tasks
- Sentiment prediction generalized well across unseen movies
- Feature importance aligned strongly with human intuition

## Tech Stack
Python, scikit-learn, NLTK, NumPy, Matplotlib, Docker, FastAPI

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebook.ipynb

