# Emotion Recognition with DistilBERT

This project fine-tunes a DistilBERT model for emotion recognition on the [dair-ai/emotion](https://huggingface.co/datasets/dair-ai/emotion) dataset, which contains Twitter messages labeled with six emotions: sadness, joy, love, anger, fear, and surprise.

## Project Overview
- **Dataset**: `dair-ai/emotion` from Hugging Face, with 16,000 training, 2,000 validation, and 2,000 test examples.
- **Model**: DistilBERT (`distilbert-base-uncased`) fine-tuned for sequence classification.
- **Task**: Classify text into one of six emotions.
- **Libraries**: Hugging Face `transformers`, `datasets`, PyTorch, NumPy.

## Requirements
To run this project, install the required Python packages:
```bash
pip install transformers datasets torch numpy
