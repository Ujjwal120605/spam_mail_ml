# spam_mail_ml
# 📧 Spam Mail Detection Using Machine Learning

This project builds a machine learning model that detects whether an email message is **spam** or **not spam (ham)** using natural language processing (NLP) techniques.

---

## 🚀 Project Overview

- **Objective**: Classify emails into `Spam` or `Ham`
- **Approach**:
  - Clean and preprocess email text data
  - Convert text into numerical features using **TF-IDF vectorization**
  - Train a **Multinomial Naive Bayes** classifier
  - Evaluate and predict on new inputs

---

## 📁 Dataset

We use the [`mail_data.csv`](./mail_data.csv) dataset with two columns:

- `Category`: either `spam` or `ham`
- `Message`: the actual email message text

Example rows:

| Category | Message                             |
|----------|-------------------------------------|
| ham      | Hey, are we still on for dinner?    |
| spam     | WIN a FREE iPhone NOW!!!            |

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- Scikit-learn
- TF-IDF (Term Frequency-Inverse Document Frequency)

---

## 📦 Requirements

Install dependencies with:

```bash
pip install pandas scikit-learn
