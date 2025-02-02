# Overview
This project aims to analyze the sentiment of Amazon Kindle reviews using various natural language processing (NLP) techniques and machine learning models. The goal is to classify reviews as positive or negative based on their content.

# Tasks Accomplished

## 1. Text Preprocessing

### Objective
Clean and preprocess the text data to prepare it for analysis.

### Actions
- **Regex:** Remove unwanted characters and symbols.
- **NLTK Library:** Remove stop words using the NLTK library.
- **Lemmatization:** Reduce words to their base or root form using lemmatization.

## 2. Vectorization

### Objective
Convert text data into numerical vectors for model training.

### Methods
- **CBOW (Continuous Bag of Words):** A word embedding technique.
- **TF-IDF (Term Frequency-Inverse Document Frequency):** A statistical measure to evaluate the importance of words in a document.

## 3. Model Building and Evaluation

### Random Forest
- **Initial Model:** Achieved 58% accuracy using TF-IDF vectorization.
- **Word Embeddings:** Implemented Word2Vec and AvgWord2Vec to reduce dimensionality.
- **Improved Model:** Achieved 62% accuracy using Word2Vec and AvgWord2Vec.

## 4. Advanced Model: LSTM RNN

### Objective
Improve model performance using a deep learning approach.

### Actions
- **LSTM RNN (Long Short-Term Memory Recurrent Neural Network):** A type of neural network well-suited for sequential data.
- **Results:** Achieved 80% accuracy, a significant improvement over previous models.

# Project Structure