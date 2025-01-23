# Amazon-Product-Reviews-Sentiment-Analysis
This project focuses on analyzing Amazon product reviews to determine customer sentiment as either positive or negative. The goal is to build a sentiment analysis model using machine learning techniques, transforming raw review text into actionable insights for better decision-making.

Key Features:
Preprocesses raw text data (cleaning, tokenization, and stopword removal).
Converts text into numerical features using TF-IDF Vectorization.
Implements a Logistic Regression model for sentiment classification.
Evaluates model performance using metrics like accuracy, precision, recall, and F1-score.
Visualizes results with a confusion matrix.

Dataset:
The dataset consists of customer reviews and their associated sentiment ratings. The ratings are converted into binary labels:

0: Negative/Neutral (rating ≤ 3)
1: Positive (rating > 3)

Project Workflow:
Data Exploration: Understand the dataset and handle missing values.
Preprocessing: Clean the text data and prepare it for modeling.
Feature Engineering: Convert text to numerical data using TF-IDF.
Model Training: Train a Logistic Regression model to classify sentiments.
Evaluation & Visualization: Analyze model performance and visualize results.
