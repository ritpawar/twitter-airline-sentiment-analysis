# Twitter Airline Sentiment & Aspect Analysis

## 📌 Project Overview
This project analyzes public sentiment toward major airlines using Twitter data.
The goal is to classify tweet sentiment (positive, neutral, negative) and identify
key service-related aspects driving customer satisfaction and dissatisfaction.

## 📊 Dataset
- Source: Kaggle – Twitter Airline Sentiment Dataset
- Size: ~14,600 tweets
- Labels: Positive, Neutral, Negative
- Additional metadata includes airline name, timestamps, and confidence scores.

## 🛠️ Approach
1. Data cleaning and preprocessing (text normalization, stopword removal)
2. Exploratory Data Analysis (sentiment distribution, airline-wise analysis)
3. Feature extraction using TF-IDF
4. Supervised learning for sentiment classification
5. Model evaluation using precision, recall, F1-score, and confusion matrix
6. Unsupervised clustering to identify service-related aspects
7. Aspect-based sentiment analysis for business insights

## 🤖 Models Used
- TF-IDF Vectorizer
- Logistic Regression / Multinomial Naive Bayes (as implemented in notebook)
- KMeans for aspect clustering

## 📈 Results
- Overall accuracy: ~75%
- Negative sentiment dominates airline-related tweets
- Key negative aspects identified include:
  - Flight delays & cancellations
  - Call center waiting time
  - Poor customer service experiences
- Positive sentiment strongly linked to helpful customer support interactions

## 💡 Key Insights
- Operational delays are the biggest drivers of negative sentiment
- Responsive customer support significantly improves public perception
- Aspect-level analysis provides actionable insights beyond overall sentiment

## 📂 Repository Structure
