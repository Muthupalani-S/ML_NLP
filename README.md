# 📧 Spam Email Detection using NLP and Machine Learning

## Overview

This project implements a Spam Email Detection system using Natural Language Processing (NLP) and the Multinomial Naive Bayes algorithm. It classifies emails as **Spam** or **Ham** by preprocessing text data and converting it into numerical features.

## Features

* Text preprocessing using NLTK
* Stopword removal
* Porter Stemming
* Feature extraction with CountVectorizer
* Spam/Ham classification using Multinomial Naive Bayes
* Performance evaluation using Accuracy, Confusion Matrix, and Classification Report

## Technologies Used

* Python
* Pandas
* NLTK
* Scikit-learn

## Workflow

1. Load the email dataset.
2. Clean and preprocess the email text.
3. Remove stopwords and apply Porter Stemming.
4. Convert text into numerical features using CountVectorizer.
5. Split the dataset into training and testing sets.
6. Train the Multinomial Naive Bayes model.
7. Evaluate the model using Accuracy, Confusion Matrix, and Classification Report.

## Project Structure

* `emails.csv` – Dataset
* `spam_detection.ipynb` – Model implementation
* `README.md` – Project documentation

## Future Improvements

* Experiment with TF-IDF Vectorizer.
* Compare multiple machine learning algorithms.
* Build a web interface using Flask or Streamlit.
* Improve model performance through hyperparameter tuning.

