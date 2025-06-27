# CT_PYTHON_TASK4
A simple machine learning project to classify SMS messages as spam or ham (not spam) using the Naive Bayes algorithm. It uses a real dataset and processes text data with CountVectorizer to build and evaluate the model.

# 📩 SMS Spam Classifier using Naive Bayes

This is a basic machine learning project that classifies SMS messages as **spam** or **ham** using a Naive Bayes algorithm.

---

## 📚 Dataset

- Source: [UCI SMS Spam Collection](https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv)
- Format: Tab-separated file with two columns — `label` (spam/ham) and `message` (text)

---

## 🚀 How it Works
1. **Preprocess** the text messages using CountVectorizer
2. **Train** a Naive Bayes model
3. **Evaluate** using accuracy and classification report

---

## 🧪 Libraries Used

- `pandas`
- `sklearn` (for model, vectorizer, and evaluation)

---
