# Twitter Sentiment Analysis

## Overview
This project implements a Twitter sentiment analysis tool using Python and machine learning techniques. The system analyzes tweets to classify them as positive or negative, providing insights into public opinion on various topics.

## Features
- Data collection from Twitter
- Split data into train and test
- Text preprocessing including stemming and stop words removal
- TF-IDF vectorization for text-to-numerical data conversion
- Logistic regression model for sentiment classification
- Model evaluation with 77.8% accuracy on test data

## Technologies Used
- Python
- Scikit-learn
- NLTK (Natural Language Toolkit)
- Pandas
- NumPy

## Installation and Setup
1. Clone this repository
2. Open the Jupyter notebook in Google Colab/VS Code
3. Run the cells in order

## Usage
You can simply use the trained model in the repository, or you can train the model yourself by:
1. Collect tweets using the provided data collection script
2. Preprocess the collected data
3. Train the model using the preprocessed data
4. Use the trained model to predict sentiment on new tweets

## Model Details
- Classification Algorithm: Logistic Regression
- Vectorization Method: TF-IDF (Term Frequency-Inverse Document Frequency)
- Preprocessing: Stemming, Stop Words Removal
- Accuracy: 79.8% on train data and 77.6% on test data

## Key Insights
- Data preprocessing is crucial for model performance
- Logistic regression is efficient for sentiment classification
- TF-IDF vectorization effectively converts text to numerical data
- Balanced dataset is important to avoid bias in model training
