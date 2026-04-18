# Next Word Prediction using Deep Learning

## Project Overview

This project is a **Next Word Prediction System** built using **TensorFlow / Keras** and **Natural Language Processing (NLP)** techniques. The model is trained on textual data to learn sentence patterns and predict the most likely next word based on a given input sequence.

The goal of this project is to understand how **Recurrent Neural Networks (RNNs)**, especially **LSTM (Long Short-Term Memory)** networks, can be used for language modeling and text generation tasks.

---

## Technologies Used

- Python  
- NumPy  
- TensorFlow / Keras  
- NLP Tokenization  
- LSTM Neural Networks  
- Bidirectional LSTM  
- GitHub for Version Control  

---

## Project Workflow

### 1. Data Collection
A text dataset is used for training. The dataset can contain daily conversation text, paragraphs, stories, articles, or any custom text corpus.

### 2. Text Preprocessing
The text data is converted into tokens using the Keras Tokenizer. Each word gets a unique numerical index.

### 3. Sequence Generation
Input sequences are created using n-gram patterns. Example:

```text
good morning how are you
