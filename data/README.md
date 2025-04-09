# 📊 Dataset: Fake and Real News

This folder contains the dataset used for training and testing fake news detection models.

## 📁 File

- `news_articles.csv` – Combined dataset of fake and real news articles.

## 📌 Source

- Originally downloaded from [Kaggle – Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

## ⚠️ Note

GitHub may not preview large `.csv` files directly. To use the dataset:

1. Open the Jupyter notebook in Google Colab.
2. Manually upload `news_articles.csv` using the file upload cell.
3. The notebook will read the file with:

```python
df = pd.read_csv("news_articles.csv")
