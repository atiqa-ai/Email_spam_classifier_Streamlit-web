# 📮 Email Spam Classifier using Machine Learning (with Streamlit Web App)

This is a Machine Learning–based Email Spam Detection System using Naive bayes that identifies whether an email is Spam or Not Spam. The project includes both the ML model and a Streamlit web application so users can test emails in real time.
🔍 Overview

The model learns patterns from a labeled dataset of emails and predicts if a new email is spam.
Text data is cleaned, transformed using TF-IDF Vectorization, and classified using a supervised ML algorithm.

## This repository includes:

Complete data preprocessing

Model training

Trained model files (model.pkl, vectorizer.pkl)

A fully working Streamlit web interface

## 🚀 How It Works

✍️ User enters email text

🧹 Text is cleaned (lowercase, remove symbols, stopwords, etc.)

🔢 TF-IDF converts text into numerical form

## 🤖 ML model predicts:

1 → Spam

0 → Not Spam

## 📊 Model Performance



🧮 Vectorizer: TF-IDF

🤖 Algorithm Used: Logistic Regression

# SVC   Accuracy:  0.93

## Random Forest  

Accuracy:  0.96

## Decision Tree  

Accuracy:  0.92

## XGBoost     

Accuracy:  0.97

## KNN Classifier  

Accuracy:  0.90

## GradientBooster  

Accuracy:  0.93

## Multinomial Naive Bayes 

Accuracy:  0.97

## 🌐 Streamlit Web App 

The UI is simple and interactive.
You can type any text email and instantly see whether it is spam.
Perfect for beginners and demonstration projects.
