# Fake News Detection

This project aims to classify news articles as True or Fake using machine learning models. A combined dataset of fake and true news articles has been prepared, and various models are applied to evaluate their performance.

## Dataset 
Dataset Source: The dataset consists of two files: <br>
- Fake.csv (contains fake news articles)
- True.csv (contains real news articles) <br>

Merged Dataset: Both datasets were combined, and a new column, class, was added: <br>
- 1 for True articles (from True.csv)
- 0 for Fake articles (from Fake.csv)

## Machine Learning Models
The following models were trained and evaluated on the dataset:

1. Logistic Regression
2. Decision Tree
3. Gradient Boosting
4. Random Forest
