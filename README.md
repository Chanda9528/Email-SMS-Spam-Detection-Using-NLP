# 📧 Email & SMS Spam Detection using NLP

## 📌 Project Overview

This project is an NLP-based Spam Detection System that classifies Email and SMS messages as **Spam** or **Not Spam**.

The system uses Natural Language Processing (NLP) techniques to clean and transform text, converts messages into numerical features using TF-IDF Vectorization, and predicts the message category using a Multinomial Naive Bayes classifier.

A user-friendly Streamlit web application is also developed for real-time predictions.

---

## 🚀 Features

- Email Spam Detection
- SMS Spam Detection
- Text Preprocessing using NLP
- TF-IDF Feature Extraction
- Multinomial Naive Bayes Classification
- Interactive Streamlit Web App
- Fast Real-time Prediction

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Scikit-learn
- NLTK
- Pandas
- NumPy
- Pickle

---

## 📂 Project Structure

```
├── app.py
├── spam_detection.ipynb
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── README.md
└── spam.csv
```

---

## 🔄 Project Workflow

1. Load Dataset
2. Data Cleaning
3. Text Preprocessing
4. Tokenization
5. Stopword Removal
6. Stemming
7. TF-IDF Vectorization
8. Model Training
9. Model Evaluation
10. Save Model
11. Deploy with Streamlit

---

## 📊 Machine Learning Model

**Algorithm Used**

- Multinomial Naive Bayes

**Feature Extraction**

- TF-IDF Vectorizer

---

## 🧹 NLP Preprocessing

- Lowercase Conversion
- Tokenization
- Remove Punctuation
- Remove Stopwords
- Stemming using Porter Stemmer

---

## ▶️ Run the Project

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

## 📸 Application

The user enters an Email or SMS message.

The system:

- Cleans the text
- Applies TF-IDF Vectorization
- Predicts Spam or Not Spam
- Displays the result instantly

---

## 📈 Future Improvements

- Deep Learning (LSTM/BERT)
- Email Attachment Analysis
- Multi-language Spam Detection
- Cloud Deployment
- Confidence Score Prediction

---

