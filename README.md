# Twitter Sentiment Analysis (BiLSTM)

An end-to-end Natural Language Processing (NLP) web application designed to classify the sentiment of tweets in real time. Built using a **Bidirectional LSTM (BiLSTM)** deep learning model in **TensorFlow/Keras**, text tokenization via **NLTK/SpaCy**, and interactive deployment through **Streamlit**.

---

## 📌 Project Overview

This project implements a deep learning pipeline to analyze text sentiment from Twitter data. By leveraging a Bidirectional LSTM layer, the model captures word context from both past and future time steps, making it well-suited for subtle textual nuances in social media data.

* **Model Framework**: TensorFlow / Keras (BiLSTM)
* **Text Preprocessing**: Tokenization and cleaning with SpaCy & NLTK
* **Interface**: Streamlit Web UI

---

## 📁 Repository Structure

```text
├── .ipynb_checkpoints/
├── .gitattributes
├── Project 2 Model Devlopment.ipynb  # Model training, EDA, and evaluation notebook
├── Twitter_Data.csv                  # Dataset used for training/validation
├── sentiment_model.h5                # Saved Keras BiLSTM trained model
├── tokenizer.joblib                  # Serialized tokenizer for text processing
├── twitter_sentiment_app.py          # Streamlit application entry point
└── README.md                         # Documentation
