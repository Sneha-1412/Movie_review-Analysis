# Movie_review-Analysis
## Overview
This project focuses on sentiment analysis for movie reviews using natural language processing (NLP) and machine learning techniques. The dataset is sourced from IMDB reviews and contains labeled sentiments (positive/negative) associated with each review.

# Project Structure
## Data Exploration and Preprocessing:

The dataset is loaded using pandas, and initial exploration is conducted to understand its structure.
Data preprocessing steps include denoising, removing special characters, and stemming to enhance the quality of the text data.

## Feature Extraction:

Two common techniques, Bag-of-Words (BoW) and TF-IDF (Term Frequency-Inverse Document Frequency), are employed to convert text data into numerical features.
Features are generated separately for training and testing sets.

## Model Training and Evaluation:

Three machine learning models—Logistic Regression, Support Vector Machine (SVM), and Multinomial Naive Bayes—are trained and evaluated on both BoW and TF-IDF features.
Model performance is assessed using accuracy scores, confusion matrices, and classification reports.

## Data Visualization:

Word clouds are generated to visually represent the most common words in both positive and negative reviews.
Bar charts illustrate the frequency of top words in negative reviews.

## Conclusion:

The project provides insights into sentiment analysis, showcasing a comprehensive pipeline from data preprocessing to model training and evaluation.

# Requirements
Python 3.x
Jupyter Notebooks
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, nltk, wordcloud
