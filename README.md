# 📰 Fake News Detection with Machine Learning

## 📘 Introduction
This project uses machine learning techniques to detect fake news by analyzing textual patterns, sentiment, and linguistic characteristics from a dataset of news articles.

## 🎯 Motivation
Fake news creates confusion and misinformation. Identifying fake news helps preserve the integrity of information online.

## 📂 Dataset
The dataset used in this project is publicly available on Kaggle:  
📎 [Fake and real news dataset – Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

- Source: Kaggle  
- Size: 2,047 news articles  
- Attributes include author, title, text, language, type, and publication date.

## ⚙️ Methodology
- **Exploratory Data Analysis (EDA)** to understand data distributions and characteristics  
- **Text Preprocessing**: Lemmatization, stop-word removal, and special character elimination  
- **Vectorization Techniques**: TF-IDF, Unigram, and N-gram features  
- **Machine Learning Models**: Multinomial Naive Bayes and Support Vector Machines (SVM)  
- **Evaluation and Tuning**: Cross-validation and hyperparameter tuning using GridSearchCV

## 📊 Results
- Best model accuracy: ~77% (SVM with Boolean features and RBF kernel)  
- Insights from sentiment analysis, topic modeling (LDA), and visualizations provided context on misinformation patterns

## 🛠️ Tools & Libraries
Python • Pandas • NumPy  
NLTK • TextBlob • VADER  
scikit-learn • Matplotlib • Seaborn  
WordCloud • Google Colab

## 👥 Contributors
- **Maybel Herrera**  
- Arti Ravi Garg  
- Rahul Gurujapu

## 📄 Final Report
A full project report summarizing methodology, analysis, results, and team contributions is available here:  
📥 [Project Report (PDF)](https://github.com/maherrer/fake-news-detection/blob/main/report/Fake_News_Project_Report.pdf)

📊 [Presentation Slides (PDF)](https://github.com/maherrer/fake-news-detection/blob/main/report/Fake_News_Project_Slides.pdf)

## 🚀 How to Run this Project (Google Colab)

1. Open the notebook directly in Google Colab:  
📔 [Open Notebook in Colab](https://colab.research.google.com/github/maherrer/fake-news-detection/blob/main/notebook/fake_news_analysis.ipynb)

2. Download the dataset from Kaggle:  
📎 [Fake and real news dataset – Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

3. In Colab, upload the CSV file manually using this code cell:
```python
from google.colab import files
uploaded = files.upload()

import pandas as pd
df = pd.read_csv("news_articles.csv")



