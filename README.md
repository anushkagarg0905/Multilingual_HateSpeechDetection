# Multilingual Hate Speech Detection using Transformers

This project implements a multilingual hate speech detection system using transformer-based language models. The objective is to classify text as hate or non-hate across multiple languages and compare the performance of two pretrained multilingual models.

---


## Project Objective

 - Detect hate speech in multilingual text

 - Compare mBERT and XLM-RoBERTa on the same dataset

 - Analyze errors across different languages

 - Present results using simple and clear visualizations

---



## Models Used

 - mBERT (bert-base-multilingual-cased)

 - XLM-RoBERTa (xlm-roberta-base)

Both models are fine-tuned using the Hugging Face Transformers library with a PyTorch backend.

---


## Methodology

 - Data cleaning and preprocessing

 - Tokenization using model-specific tokenizers

 - Fine-tuning transformer models for binary classification

 - Evaluation using standard classification metrics

 - Model comparison and language-wise error analysis


---

## Evaluation Metrics

 - Accuracy

 - Precision

 - Recall

 - F1-Score

 - Confusion Matrix


---

## Analysis and Visualization

 - Comparison of mBERT and XLM-RoBERTa performance

 - Language-wise error rate analysis

 - Simple graphs for performance interpretation

---


## Technologies Used

 - Python

 - PyTorch 

 - Hugging Face Transformers

 - Scikit-learn

 - Pandas, NumPy

 - Matplotlib, Seaborn

 - Google Colab
