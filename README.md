 
# Fake News Data Classification

This repository contains code for a machine learning project focused on detecting fake news. The project utilizes Python and various libraries such as Pandas, NumPy, Matplotlib, NLTK, and Scikit-learn.

Implemented a Natural Language Processing(NLP) based fake news detection system using NLTK and Scikit-learn, achieving an 88% accuracy and F1 score. Conducted comprehensive data cleaning and text preprocessing, including the removal of stop words, to enhance model performance. Utilized advanced NLP techniques such as TF-IDF for feature engineering, improving the model's ability to discern between fake and real news. 

## Overview

Fake news has become a significant issue in today's information age, where misinformation can spread rapidly through various media channels. This project aims to build a machine learning model that can automatically detect fake news articles based on their content.

##Libraries Used:##
- **pandas:** Used for data manipulation and analysis.
- **numpy:** Provides support for mathematical functions and operations on arrays.
- **matplotlib:** A plotting library used for data visualization.
- **re:** Offers support for regular expressions, helpful for text preprocessing.
- **seaborn:** Works alongside matplotlib for enhanced data visualization.
- **nltk:** Natural Language Toolkit, used for text processing tasks such as stopword removal and stemming.
- **scikit-learn (sklearn):**
  - **TfidfTransformer and TfidfVectorizer:** Used for feature extraction from text data using TF-IDF (Term Frequency-Inverse Document Frequency).
  - **train_test_split:** For splitting the dataset into training and testing sets.
  - **LogisticRegression:** Implements logistic regression, a commonly used classification algorithm.
  - **accuracy_score:** Calculates the accuracy of the model.

## Dataset

The dataset used in this project contains a collection of news articles labeled as either fake or real. It includes various features such as the title, text, and other metadata.

## Approach

1. **Data Preprocessing**: Text data is cleaned and preprocessed using techniques such as removing stopwords, stemming, and vectorization.
2. **Feature Engineering**: Text features are extracted using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
3. **Model Training**: The preprocessed data is split into training and testing sets. A logistic regression model is trained on the training data.
4. **Model Evaluation**: The trained model is evaluated on the test set using accuracy as the performance metric.


**Project Workflow:**
1. **Data Loading:** The project likely starts with loading a dataset containing both real and fake news articles.
2. **Data Preprocessing:**
   - Text Cleaning: Removing unnecessary characters, special symbols, and URLs.
   - Tokenization: Splitting the text into individual words or tokens.
   - Stopword Removal: Eliminating common words that do not carry significant meaning.
   - Stemming: Reducing words to their root form to normalize the text.
3. **Feature Extraction:** Using TF-IDF to convert text data into numerical vectors.
4. **Model Training:** Splitting the data into training and testing sets, then training a logistic regression model on the training data.
5. **Model Evaluation:** Evaluating the trained model's performance using accuracy metrics on the testing set.
6. **Deployment:** After successful evaluation, the model can be deployed to predict fake news on new data.

