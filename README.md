# VerifAI: Fake News Detection using BERT and LSTM

## Overview

VerifAI is an NLP-based fake news detection system that explores deep learning and transformer-based approaches for classifying news articles as **Real** or **Fake**. The project compares multiple text classification techniques and aims to build interpretable and reliable misinformation detection systems.

## Features

* Fake news classification using deep learning models
* Comparative study of BERT and LSTM architectures
* Text preprocessing and tokenization pipelines
* Model evaluation using standard classification metrics
* Extensible framework for explainability and deployment

## Tech Stack

* Python
* NumPy
* Pandas
* Scikit-learn
* TensorFlow / Keras
* Hugging Face Transformers
* Jupyter Notebook

## Models Implemented

### 1. BERT-Based Classifier

* Transformer-based contextual embeddings
* Fine-tuned for binary fake news classification
* Designed for high semantic understanding of news content

### 2. LSTM-Based Classifier

* Sequential deep learning model for text classification
* Utilizes token embeddings and recurrent neural networks
* Provides a baseline for comparison with transformer models

## Project Structure

```text
VerifAI/
├── bert_fake_news_classifier.ipynb
├── lstm_fake_news_classifier.ipynb
├── dataset/
├── results/
├── requirements.txt
└── README.md
```

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Future Enhancements

* Streamlit-based interactive dashboard
* Confidence score generation
* Explainable AI and attention visualization
* Real-time news credibility assessment
* Multi-modal fake news detection using text and images

## Learning Outcomes

Through this project, I aim to strengthen my understanding of:

* Natural Language Processing (NLP)
* Deep Learning for text classification
* Transformer architectures (BERT)
* Sequence models (LSTM)
* Model evaluation and experimentation

