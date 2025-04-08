
# Fake News Detection with Machine Learning

## Introduction
This project uses machine learning techniques to detect fake news by analyzing textual patterns, sentiment, and linguistic characteristics from a dataset of news articles.

## Motivation
Fake news creates confusion and misinformation. Identifying fake news helps preserve the integrity of information online.

## Dataset
- Source: Kaggle
- Size: 2047 news articles
- Attributes include author, title, text, language, type, and publication date.

## Methodology
- **Exploratory Data Analysis (EDA)** to understand data distributions and characteristics.
- **Text Preprocessing**: Lemmatization, stop-word removal, and special character elimination.
- **Vectorization Techniques**: TF-IDF, Unigram, and N-gram features.
- **Machine Learning Models**: Multinomial Naive Bayes and Support Vector Machines (SVM).
- **Evaluation and Tuning**: Cross-validation and hyperparameter tuning using GridSearchCV.

## Results
- Best model accuracy: Approximately 77% (SVM with Boolean features and RBF kernel).
- Insights from sentiment analysis, topic modeling (LDA), and visualizations provided context on misinformation patterns.

## Technologies Used
- Python
- Pandas, NumPy
- NLTK, TextBlob
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Contributors
- Maybel Herrera
- Other Team Members: Arti Ravi Garg, Rahul Gurujapu

## How to Run this Project
1. Clone the repository:
```bash
git clone https://github.com/maherrer/fake-news-detection.git
