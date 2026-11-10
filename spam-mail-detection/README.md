# SMS Spam Detector

An NLP-based machine learning project that classifies SMS messages as spam or ham.

## Project Overview

Spam messages are unwanted or fraudulent messages that may contain advertisements, scams, or misleading links. This project uses Natural Language Processing and Machine Learning to automatically classify messages into two categories:

- Spam
- Ham (legitimate message)

## Features

- Text preprocessing
- Lowercasing and punctuation removal
- Tokenization
- Stopword removal
- TF-IDF feature extraction
- Logistic Regression classification
- Accuracy, precision, recall, and F1-score evaluation
- Custom message prediction

## Dataset

The project uses the SMS Spam Collection dataset.

It contains labelled SMS messages divided into:

- `ham` — legitimate messages
- `spam` — unwanted messages

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Machine Learning Workflow

```text
Raw SMS Dataset
      ↓
Text Preprocessing
      ↓
Train-Test Split
      ↓
TF-IDF Feature Extraction
      ↓
Logistic Regression
      ↓
Prediction
      ↓
Model Evaluation

Model Performance


| Metric         | Score |
| -------------- | ----: |
| Accuracy       |   96% |
| Ham Precision  |  0.96 |
| Ham Recall     |  1.00 |
| Spam Precision |  1.00 |
| Spam Recall    |  0.72 |
| Spam F1-score  |  0.84 |
