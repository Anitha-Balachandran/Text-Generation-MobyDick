# Mini-Project Summary: Text Generation with MOBY-DICK Book Data

## Overview:
This mini-project focuses on generating text using data from at least five chapters of the MOBY-DICK book. The objective is to develop a text generation model that can produce coherent and diverse text based on the patterns learned from the book.

## Implemented Tasks:

### 1. Data Preparation:
- Extracted text data from MOBY-DICK book, specifically from five or more chapters.
- Preprocessed the text by tokenization, converting to lowercase, expanding contractions, removing punctuation, and applying lemmatization or stemming.

### 2. Model Development:
- Developed a multiclass classification sequential model (e.g., GRU/LSTM/RNN) using Keras word embeddings for text generation.
- Used a sequence length of at least 25 tokens as X features and predicted the immediate next token as the Y feature.
- Trained the model to generate text that is diverse and meaningful, ensuring it does not consist solely of identical words and contains a minimum of 50 words (tokens).

### 3. Transfer Learning:
- Explored transfer learning techniques using Word2Vec, GloVe, and ELMo word embeddings for text generation.
- Leveraged pre-trained embeddings to enhance the quality and diversity of the generated text.
- Utilized cosine similarity to identify the five words most similar to "whale" based on the trained word embeddings.

## Conclusion:
This mini-project showcases the implementation of text generation techniques using deep learning models and transfer learning with various word embeddings. The generated text reflects the style and context of the MOBY-DICK book, contributing to advancements in natural language processing and creative text generation.
