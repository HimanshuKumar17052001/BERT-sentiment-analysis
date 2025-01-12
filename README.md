# Sentiment Analysis Using BERT

This repository demonstrates how to perform sentiment analysis using the pre-trained **BERT** model from the Hugging Face Transformers library. The project covers data preprocessing, fine-tuning, evaluation, and deployment of a sentiment analysis model that predicts sentiments such as **Positive**, **Neutral**, and **Negative** for given text inputs.

---

## Features
- **BERT-based Sentiment Analysis**: Fine-tunes the `bert-base-uncased` model for sentiment classification.
- **Customizable Pipeline**: Easily replace datasets or modify for different NLP tasks.
- **Evaluation Metrics**: Includes accuracy, precision, recall, and F1 score for model performance assessment.
- **Data Visualization**: Plots for training/validation accuracy and loss trends.
- **Deployment-Ready Code**: Save and load the fine-tuned model for inference on new data.

---

## Project Overview
### 1. Preprocessing
- Cleans and preprocesses text data, including handling missing values and tokenization.
- Converts labels into numerical values for training and evaluation.

### 2. Model Training
- Fine-tunes the `bert-base-uncased` model using labeled sentiment data.
- Implements training loops with gradient optimization and learning rate scheduling.

### 3. Evaluation
- Evaluates the model on unseen test data.
- Outputs a detailed classification report with metrics.

### 4. Testing and Inference
- Allows testing on individual text inputs or entire datasets.
- Includes a robust prediction function for real-time sentiment analysis.
