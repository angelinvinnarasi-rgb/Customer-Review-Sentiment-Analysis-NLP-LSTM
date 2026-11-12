# Customer Review Sentiment Analysis using NLP and LSTM

## Project Overview
This project focuses on analyzing customer reviews and classifying them into two sentiment categories: **Positive** and **Negative** using Natural Language Processing (NLP) and a Long Short-Term Memory (LSTM) neural network.

The project uses the built-in IMDB movie review dataset from Keras to train and evaluate a deep learning model.

## Objectives
- Preprocess and clean review text.
- Perform tokenization and sequence generation.
- Explore text representation techniques such as Bag of Words (BoW), TF-IDF, and Word Embeddings.
- Build and train an LSTM-based sentiment classification model.
- Evaluate model performance using classification metrics and visualizations.

## Technologies Used
- Python
- TensorFlow / Keras
- Natural Language Processing (NLP)
- NumPy
- Pandas
- NLTK
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Dataset
**IMDB Movie Reviews Dataset**

- Training samples: 25,000
- Testing samples: 25,000
- Classes: Positive and Negative
- Vocabulary size: 10,000 words

## Project Workflow

1. **Text Preprocessing**
   - Text cleaning
   - Tokenization
   - Stopword removal
   - Lemmatization
   - Sequence generation
   - Padding

2. **Text Representation**
   - Bag of Words (BoW)
   - TF-IDF
   - Word Embeddings

3. **LSTM Model Development**
   - Embedding layer
   - LSTM layer
   - Dense layers
   - Dropout regularization
   - Binary classification

4. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion matrix
   - Performance graphs

5. **Performance Analysis**
   - Sequence length analysis
   - Importance of embeddings
   - Overfitting analysis
   - Model limitations and improvements

## Model Performance

| Metric | Result |
|---|---:|
| Test Accuracy | 80.85% |
| Precision | 75.06% |
| Recall | 92.39% |
| F1-score | 82.83% |

## Project Structure

```text
Customer_Review_Sentiment_