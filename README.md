# 📊 Sentiment Analysis on IMDB Reviews with LSTM
This project demonstrates how to build a Sentiment Analysis model using Long Short-Term Memory (LSTM) networks on the IMDB movie reviews dataset. The goal is to classify movie reviews as either positive or negative.

# Overview
Natural Language Processing (NLP) task.

Preprocessed textual data using tokenization and padding.

Used an embedding layer followed by LSTM layers.

Built using TensorFlow/Keras for deep learning.

Achieved good performance for binary classification.

# 📂 Dataset
We used the IMDB dataset provided by Keras.datasets, which contains:

25,000 labeled training reviews.

25,000 labeled test reviews.

Preprocessed: reviews are converted into sequences of integers.

# 🛠️ Technologies Used
Python

TensorFlow / Keras

NumPy

Matplotlib

Seaborn

## 📈 Model Architecture

# Input (Tokenized & Padded Sequences)
        ↓
# Embedding Layer (32 Dimensions)
        ↓
# LSTM Layer (100 units)
        ↓
# Dense Layer (1 unit with sigmoid activation)
        ↓
# Binary Output (Positive / Negative)

# 📊 Results
Training Accuracy: ~98%

Validation Accuracy: ~87%

Loss and Accuracy curves show minimal overfitting.

The model performs well on unseen data.
