# Spam_Mail_Detection
This project builds a spam mail detection system using machine learning and TensorFlow. An LSTM-based model is trained on labeled email text data using NLP techniques to classify messages as spam or non-spam, achieving reliable accuracy through proper preprocessing, training, and evaluation.

Spam Mail Detection is an end-to-end machine learning project designed to automatically classify email messages as Spam or Not Spam (Ham) using Natural Language Processing (NLP) and deep learning techniques. The project focuses on text preprocessing, sequence modeling, and performance evaluation using a TensorFlow-based LSTM model.

### Dataset

<a href="https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection">SMS Spam Collection Dataset (UCI)</a>

The dataset consists of labeled email/message text data categorized as spam or non-spam, commonly used for spam classification tasks.

### Process

Cleaned and preprocessed raw text data (lowercasing, tokenization, padding)

Converted textual data into numerical sequences using NLP techniques

Built and trained an LSTM-based deep learning model using TensorFlow/Keras

Evaluated model performance using accuracy, precision, recall, and F1-score

Implemented command-line based prediction for real-time spam detection

### Model

Algorithm: LSTM (Long Short-Term Memory)

Framework: TensorFlow / Keras

Task: Binary Classification (Spam vs Not Spam)

### Key Results

Achieved high classification accuracy (~94%)

Balanced precision and recall for reliable spam detection

Effectively captured sequential and contextual patterns in email text

Demonstrated robustness on unseen email inputs

Outcome

The project showcases practical experience in NLP, deep learning, and end-to-end machine learning workflows. It provides a strong foundation for further enhancements such as web-based deployment, API integration, or real-world email filtering systems.
