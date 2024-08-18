# Next-Word-Predictor

This project implements a Bidirectional LSTM (BiLSTM) model for text sequence prediction using PyTorch. The primary goal is to predict the next word in a sequence based on previous words. The code includes data preprocessing, tokenization, and vocabulary creation, as well as the handling of out-of-vocabulary (OOV) tokens.

Key features of the project include:

-- Text Preprocessing: Cleans the text by removing HTML tags, emojis, and special characters, and converts numbers to words.
-- Tokenization and Vectorization: Converts text into numerical sequences, with support for adding OOV tokens to improve model robustness.
-- BiLSTM Model: A custom BiLSTM model is designed with an embedding layer, bidirectional LSTM, and a fully connected layer for sequence prediction.
--Training and Evaluation: The model is trained with cross-entropy loss and Adam optimizer, and the performance is evaluated using top-k accuracy on training and test datasets.
--Early Stopping: Implements early stopping to prevent overfitting based on validation loss.

## Authors
- Raul Om Deepak
- Rudra Panch
- Rachit Kumar
