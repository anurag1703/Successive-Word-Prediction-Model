# Next Word Prediction using LSTM and RNN

This project implements a Next Word Prediction model using Long Short-Term Memory (LSTM) and Recurrent Neural Networks (RNN). The model takes a sequence of words as input and predicts the most likely next word in the sentence. The application is deployed using Streamlit for an interactive interface.\

# Overview

The Next Word Prediction model is designed to assist in text generation tasks by predicting the next word in a sentence based on the input context. This is useful in various NLP applications such as text autocompletion, writing assistants, and chatbot responses

# Architecture

The project uses two types of neural networks:

~LSTM (Long Short-Term Memory): For handling long-term dependencies in the text.

~RNN (Recurrent Neural Networks): For processing sequences of words and predicting the next word based on previous context.

The architecture includes:

~Embedding Layer: To convert words into vector representations.

~LSTM/RNN Layers: For processing the sequence data.

~Dense Layer: For outputting the predicted next word.

# Dataset

The model is trained on a text dataset that contains a large collection of sentences. It uses word tokenization to split sentences into words and then prepares input sequences for training the LSTM and RNN models. The dataset can be a corpus such as:

-News articles

-Literary works (e.g., from Project Gutenberg)

-Other NLP datasets

# Results
The model achieves good performance in next word prediction, especially in structured text, showing accuracy in context-based predictions. However, accuracy may vary depending on the dataset and the complexity of sentences.