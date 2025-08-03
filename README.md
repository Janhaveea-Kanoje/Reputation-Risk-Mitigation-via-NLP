#  Fake News Detection for Risk Mitigation

## Project Overview
This project aims to build an NLP-based pipeline that automatically identifies fake news articles. It enables organizations to minimize misinformation risks and make informed decisions by leveraging machine learning models trained on labeled news content.

## Problem Statement
With the rise in digital content, fake news spreads rapidly, impacting public perception and damaging reputations. Manual verification is inefficient and unscalable. This project automates the detection process using machine learning and NLP.

## Data Source
- [Kaggle Fake News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
- Contains labeled news articles marked as “real” or “fake” with metadata and full content.

## Steps Performed
1. **Data Cleaning**: Removed duplicates, nulls, stopwords, and punctuation.
2. **Text Preprocessing**: Tokenization, lemmatization, and lowercasing.
3. **Vectorization**: Compared TF-IDF, Word2Vec, and BERT embeddings.
4. **Modeling**: Trained Logistic Regression, Random Forest, and BERT-based classifiers.
5. **Evaluation**: Assessed models using accuracy, precision, recall, and F1-score.

## ⚙ Requirements
- Python 3.8+
- pandas
- scikit-learn
- gensim
- transformers
- nltk
- matplotlib
- jupyter

```bash
pip install -r requirements.txt

