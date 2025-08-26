# Installing NLTK and Configuring the Python Environment

This repository contains a Jupyter Notebook for **Sentiment Analysis** using **NLTK** and **scikit-learn**.  
The notebook demonstrates a complete pipeline: loading data, text preprocessing, feature vectorization, training classification models, and evaluating them with metrics and visualizations.

## 🚀 Objectives
- Clean and normalize text (lowercasing, punctuation removal, stopwords removal, lemmatization/stemming).
- Convert text into numerical features (*TfidfVectorizer (assumed)*).
- Evaluate performance (*accuracy_score, classification_report, confusion_matrix*), with visualizations (*matplotlib, seaborn*).

## 📓 Contents
- Notebook: `NLTK-Sentiment-Analysis.ipynb`  
- Dataset(s):  `amazon sentiment analysis dataset` available on `https://raw.githubusercontent.com/pycaret/pycaret/master/datasets/amazon.csv`
-

## 🧰 Requirements
- Python 3.9+  
- Jupyter Notebook/Lab  

### Main Dependencies
```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn
