# Sentiment Analysis on IMDb Reviews (TF-IDF + Logistic Regression)

## Overview

This project builds a sentiment analysis model that classifies IMDb movie reviews as **positive** or **negative** using **TF-IDF vectorization** and **Logistic Regression**. It demonstrates a complete classical NLP pipeline from dataset loading to prediction.

## Dataset

* Source: `tf.keras.datasets.imdb`
* Total samples: 50,000 reviews
* Training: 25,000
* Testing: 25,000
* Task: Binary sentiment classification

## Tech Stack

* Python
* TensorFlow
* Scikit-learn
* NumPy

## Workflow

1. Load IMDb dataset
2. Decode encoded reviews into text
3. Convert text to features using TF-IDF
4. Train Logistic Regression model
5. Evaluate accuracy and classification report
6. Predict sentiment for custom input sentences

## Results

* Model: Logistic Regression
* Features: TF-IDF (top 5000 words)
* Accuracy: ~88–90%

## Example Predictions

* "This movie was amazing!" → Positive
* "Worst acting I have ever seen." → Negative

## Future Improvements

* Use Word2Vec / GloVe embeddings
* Train LSTM or BERT-based model
* Deploy with Streamlit or FastAPI

## Author

Built as a portfolio NLP project demonstrating text preprocessing, feature engineering, and sentiment classification using classical machine learning techniques.
