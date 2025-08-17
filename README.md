# 📰 Fake News Detector
A machine learning project that detects whether a news article is **FAKE** or **TRUE** using Natural Language Processing (NLP) and Logistic Regression.

## Overview
This project aims to classify news articles based on their text content using basic NLP preprocessing and a TF-IDF-based Logistic Regression model.

## 📊 Dataset
The dataset contains two CSV files:
- `Fake.csv` — Fake news articles
- `True.csv` — True news articles

Each file includes:
- `title`
- `text`
- `subject`
- `date`

## 🧰 Tech Stack
- Python 
- Pandas
- Scikit-learn
- Matplotlib
- TF-IDF (Text Preprocessing)

## 🔍 Workflow
1. Load and merge the dataset
2. Clean and preprocess text
3. Transform text using TF-IDF Vectorizer
4. Train logistic regression model
5. Evaluate with accuracy score, classification report, and confusion matrix

