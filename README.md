# 📮 Email Spam Classifier using Machine Learning (with Streamlit Web App)

This is a Machine Learning–based Email Spam Detection System using Naive bayes that identifies whether an email is Spam or Not Spam. The project includes both the ML model and a Streamlit web application so users can test emails in real time.
🔍 Overview

The model learns patterns from a labeled dataset of emails and predicts if a new email is spam.
Text data is cleaned, transformed using TF-IDF Vectorization, and classified using a supervised ML algorithm.

This repository includes:

Complete data preprocessing

Model training

Trained model files (model.pkl, vectorizer.pkl)

A fully working Streamlit web interface

🚀 How It Works

✍️ User enters email text

🧹 Text is cleaned (lowercase, remove symbols, stopwords, etc.)

🔢 TF-IDF converts text into numerical form

🤖 ML model predicts:

1 → Spam

0 → Not Spam

📊 Model Performance

🎯 Accuracy: 

sr Model Accuracy Precision
1  KN 	0.904255	1.000000
2	 RF	  0.967118	1.000000
3	 ETC	0.971954	0.991525
4	 LR 	0.970986	0.945736
5	 xgb	0.970019	0.945312
6	 DT	  0.924565	0.935065
7	 NB 	0.973888	0.888158
8	 GBDT	0.934236	0.881188
9	 SVC	0.932302	0.773723


🧮 Vectorizer: TF-IDF

🤖 Algorithm Used: Logistic Regression

# SVc

# Random Forest

# Decision Tree

# XGBoost 

# KNN Classifier

# GradientBooster

# Multinomial Naive Bayes

# 🌐 Streamlit Web App

The UI is simple and interactive.
You can type any text email and instantly see whether it is spam.
Perfect for beginners and demonstration projects.
