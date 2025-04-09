# 📧 Spam Detection using Machine Learning

This project is a machine learning-based **spam classifier** that analyzes and classifies text messages as **spam** or **ham (not spam)**. It uses natural language processing (NLP) techniques along with popular ML models like Naive Bayes to build a robust spam detection system.

---

## 🚀 Features

- Clean and preprocess raw text messages
- Exploratory Data Analysis (EDA)
- Text vectorization using TF-IDF
- Train a classifier to detect spam messages
- Model evaluation and accuracy metrics
- Ready for deployment

---

## 🛠️ Tech Stack

- **Language**: Python 🐍
- **Libraries**:
  - `pandas`, `numpy` for data handling
  - `matplotlib`, `seaborn` for EDA
  - `sklearn` for model building and evaluation
  - `nltk` for natural language processing

---

## 📂 Dataset

We used a classic dataset for spam classification:

- Contains **SMS messages** labeled as either `ham` or `spam`
- Format: `.tsv` with two columns: `label` and `message`

---

## 📋 Project Workflow

### 1. Import Libraries
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import nltk
