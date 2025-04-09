
# Fake News Detection with Machine Learning

## Introduction
This project uses machine learning techniques to detect fake news by analyzing textual patterns, sentiment, and linguistic characteristics from a dataset of news articles.

## Motivation
Fake news creates confusion and misinformation. Identifying fake news helps preserve the integrity of information online.

- ## Dataset

The dataset used in this project is publicly available on Kaggle:

📎 [Fake and real news dataset – Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
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
- 
- ## 📄 Final Report

A full project report summarizing methodology, analysis, results, and team contributions is available here:

📥 [Download the Final Report (PDF)](https://github.com/maherrer/fake-news-detection/blob/main/report/Project_Report_FakeNews.pdf)

  

## 🚀 How to Run this Project (Google Colab)

1. Open the notebook directly in Google Colab:  
📔 [fake_news_analysis.ipynb](https://github.com/maherrer/fake-news-detection/blob/main/notebook/fake_news_analysis.ipynb)

2. Download the dataset from Kaggle:  
📎 [Fake and real news dataset – Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

3. In Colab, upload the CSV file manually using this code cell:

```python
from google.colab import files
uploaded = files.upload()

import pandas as pd
import io
df = pd.read_csv("news_articles.csv")

🔸 Important: Make sure the uploaded file is named exactly:
news_articles.csv

Your notebook is set up to load it using:
df = pd.read_csv("news_articles.csv")



