Next Word Predictor using LSTM

This file demonstrates a fundamental Natural Language Processing (NLP) task: Next Word Prediction. Using TensorFlow and Keras, the model learns from a small corpus of conversational text to predict the most likely succeeding word given a seed phrase.

Overview:

1. The pipeline transforms raw text into a format suitable for deep learning by:

2. Tokenization: Converting words into unique integer IDs.

3. N-Gram Generation: Breaking sentences into incremental sequences (e.g., "I am" -> "running").

4. Padding: Ensuring all input sequences are the same length for the neural network.

5. Modeling: Utilizing an Embedding layer and an LSTM layer to capture the sequential context of the language
   
