# Retail Data Science Projects

Three analyses from a freelance data science engagement our team took on in 2022, each built on a public dataset.

| Notebook | Question | Methods | Data |
|---|---|---|---|
| [`online_retail_segmentation.ipynb`](online_retail_segmentation.ipynb) | Which customer segments does an online retailer have? | Recency, frequency and monetary (RFM) features, outlier removal, k-means clustering chosen by elbow and silhouette scores | UCI Online Retail dataset |
| [`reviews_sentiment_analysis.ipynb`](reviews_sentiment_analysis.ipynb) | Can review text predict whether a review is positive or negative? | Text cleaning and deduplication, bag-of-words, TF-IDF and Word2Vec features, naive Bayes classifiers evaluated by ROC AUC | Amazon Fine Food Reviews (Kaggle) |
| [`walmart_sales_forecasting.ipynb`](walmart_sales_forecasting.ipynb) | How well can weekly store sales be forecast? | Stationarity checks, ARIMA and auto-ARIMA, Prophet, random forest and LSTM models | Walmart sales dataset (Kaggle) |

The notebooks were run in Google Colab and locally, and they keep their saved outputs. To rerun them, download the datasets and change the file paths in the loading cells.

This repository is my fork of the team's repository, [ayushgodbole17/Project-Crayola](https://github.com/ayushgodbole17/Project-Crayola).
