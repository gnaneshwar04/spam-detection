# 📧 Spam Detection using SVM

This project implements a **Spam Detection System** using the **Support Vector Machine (SVM)** algorithm. It processes SMS messages to classify them as either **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques and machine learning.

---

## 🔍 Problem Statement

With the rising volume of text-based communication, spam messages have become a growing concern. Manually identifying spam is inefficient and error-prone. The goal is to build an automated system that accurately classifies SMS messages as spam or ham.

---

## ✅ Proposed Solution

The system uses a machine learning approach with the following steps:
- Load and clean the SMS dataset
- Preprocess text using NLP techniques
- Extract features using **TF-IDF vectorization**
- Train an **SVM model** on the processed data
- Evaluate performance using metrics like accuracy, precision, recall, and F1-score

---

## 🛠️ System Requirements

### Libraries and Tools
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib (for optional visualizations)
- nltk (for text processing)

Install dependencies using:
```bash
pip install -r requirements.txt
