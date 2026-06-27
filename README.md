# Sentiment Analysis using YouTube Comments Dataset

## Overview

This project performs **Natural Language Processing (NLP)** and **Machine Learning** to classify YouTube comments as **Positive** or **Negative**.

The system preprocesses raw text, extracts meaningful features using TF-IDF, and trains a Multinomial Naive Bayes classifier to perform sentiment prediction.

The project demonstrates a complete text analytics pipeline for large-scale unstructured data.

---

## Problem Statement

Millions of YouTube comments are generated daily. Understanding user sentiment can help businesses and content creators evaluate audience engagement and public opinion.

This project builds an automated sentiment analysis model capable of processing large volumes of textual data.

---

## Dataset

* Source: Kaggle
* Dataset: US YouTube Comments
* Total Dataset Size: ~691,400 comments
* Sample Used: 20,000 comments

---

## NLP Pipeline

Raw Comments

↓

Text Cleaning

↓

Tokenization

↓

TF-IDF Feature Extraction

↓

Feature Selection

↓

Multinomial Naive Bayes

↓

Sentiment Prediction

---

## Text Preprocessing

* Lowercasing
* URL Removal
* Special Character Removal
* Tokenization
* Stopword Handling
* Stemming/Lemmatization

---

## Feature Engineering

* Bag of Words
* TF-IDF Vectorization
* Term Document Matrix
* Corpus Construction
* Feature Selection

---

## Machine Learning Model

* Multinomial Naive Bayes (MNB)

Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* Google Colab

---

## Project Structure

```
Sentiment-Analysis-YouTube/

│── Sentiment_Analysis.ipynb
│── Sentiment Analysis using YouTube Comments Dataset.pdf
│── UScomments.csv
│── screenshots/
│── README.md
```

---

## Results

* Cleaned and preprocessed text data
* Generated TF-IDF feature vectors
* Trained Multinomial Naive Bayes classifier
* Achieved approximately **97% classification accuracy**
* Visualized results using confusion matrix and accuracy plots

---

## Future Enhancements

* Deep Learning using LSTM
* BERT-based Sentiment Analysis
* Transformer Models
* Real-time YouTube Comment Analysis
* Web Deployment using Flask

---

## Author

**Manjushree D**
VIT Chennai
