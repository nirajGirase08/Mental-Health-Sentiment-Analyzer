# 🧠 Mental Health Sentiment Analyzer

A machine learning-based sentiment analysis tool designed to detect and classify mental health-related statements into various psychological conditions. This project aims to support early detection and awareness of mental health issues by analyzing textual data using Natural Language Processing (NLP) techniques and classification models.

---

## 📌 Project Overview

The **Mental Health Sentiment Analyzer** classifies user-input text into one of the following seven mental health categories:

- **Anxiety**
- **Depression**
- **Normal**
- **Suicidal**
- **Stress**
- **Bipolar**
- **Personality disorder**

By leveraging TF-IDF vectorization and various ML classifiers such as Random Forest and Logistic Regression, this tool attempts to understand and classify mental health sentiment from raw text.

---

## 🛠️ Features

- Text preprocessing: cleaning, tokenization, stopword removal, and lemmatization
- TF-IDF vectorization to extract important features
- Support for imbalanced datasets using **SMOTE** (Synthetic Minority Over-sampling Technique)
- Multiple model training and evaluation
- Predict sentiment from new input statements

---

## 📁 Dataset

- The dataset is sourced from **Kaggle** and is available in the project folder (`data/mental_health_data.csv` or similar).
- Each entry is labeled with one of the seven mental health categories.
- Preprocessing includes:
  - Lowercasing
  - Removing punctuation/special characters
  - Removing stopwords
  - Lemmatizing words

---

## 🔍 Model Training & Evaluation

- Models used: `Random Forest`, `Logistic Regression` (others can be easily added)
- Evaluation metrics:
  - Accuracy
  - Confusion Matrix
  - Classification Report
- SMOTE was applied to handle class imbalance before model training.

---

## 🔮 Prediction Pipeline

1. **Input:** Raw user sentence
2. **Preprocessing:** Clean, tokenize, remove stopwords, lemmatize
3. **Vectorization:** TF-IDF
4. **Prediction:** Output predicted mental health category

---
### 📦 Install Required Libraries

Run the following command to install the dependencies:

```bash
pip install -r requirements.txt
   
