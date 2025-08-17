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

## How it Works

1. **Data Loading**  
   Combined `Fake.csv` and `True.csv` datasets with appropriate labels.

   ![Data Loading](images/01_data loading.png)

2. **Data Preprocessing & Splitting**  
   TF-IDF Vectorizer used to transform the text. Data split into train and test sets.

3. **Model Training**  
   Trained using a Passive Aggressive Classifier.

4. **Evaluation**  
   Achieved an accuracy of `98.99%` .  
   Below is the confusion matrix:

   ![Confusion Matrix](images/03_confusion matrix.png)
