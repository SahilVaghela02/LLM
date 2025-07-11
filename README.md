# Emotion Detection with BERT

This project uses a BERT-based model to detect emotions in text. It is trained on the [Emotion Dataset (GoEmotions or Emotion)] and classifies input into one of six emotions: **anger**, **fear**, **joy**, **love**, **sadness**, or **surprise**.

## 🔍 Overview

The goal of this project is to leverage the power of BERT to accurately identify emotions expressed in textual data. This can be useful for applications in customer feedback analysis, sentiment tracking, conversational agents, and more.

> Dataset used: [Emotion Dataset](https://huggingface.co/datasets/emotion) from Hugging Face Datasets library.

## 🧠 Model

- Base model: `bert-base-uncased`
- Fine-tuned using Hugging Face Transformers and PyTorch
- Tokenization: `BertTokenizer`
- Architecture: BERT + classification head (linear layer)

## 🚀 Features

- Train BERT on the 6-class Emotion dataset
- Evaluate on validation/test set with metrics like accuracy and F1-score
- Predict emotion from raw text input
- Export model for inference

## ⚙️ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/yourusername/emotion-detection-bert.git
cd emotion-detection-bert
pip install -r requirements.txt

