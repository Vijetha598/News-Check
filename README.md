# News-Check
# Overview
News Check is a machine learning-based fake news detection system that analyzes the text content of articles and determines their authenticity. Using Natural Language Processing (NLP) and Machine Learning (ML) techniques, this model classifies news as either real or fake.
The trained model is deployed using Flask, providing a simple web interface where users can enter a news article and check its authenticity.

# Features
Machine Learning Model: Trained using Logistic Regression, Random Forest, Naïve Bayes.
NLP-Based Analysis: Preprocessing includes text cleaning, removing stopwords, and vectorization.
Web Application: Built using Flask.
Dataset: Publicly available datasets from Kaggle containing labeled fake and real news articles.
Accuracy: The best-performing model achieves 87.04% accuracy on 60,000+ records.

# Technologies Used
Programming Language: Python 3.9
Machine Learning Libraries: Scikit-learn, NLTK, NumPy, Pandas
Data Visualization: Matplotlib, Seaborn
Model Deployment: Flask

# Dataset
The dataset contains news articles labeled as real (1) or fake (0). 

# Data preprocessing includes:
Removing unnecessary columns
Cleaning punctuation, numbers, and URLs
Combining headlines and text for better context

# Model Training & Evaluation
ML Models Tested: Logistic Regression, Random Forest, Decision Tree, XGBoost, Naive Bayes.
Best Model: Logistic Regression (87.04% accuracy)
Performance Metrics: Accuracy, Confusion Matrix
