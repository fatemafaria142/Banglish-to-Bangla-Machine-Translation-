# Banglish-to-Bangla Neural Machine Translation

This repository contains code and resources for a neural machine translation model that translates text from Banglish (a blend of Bengali and English) to Bangla. The model architecture utilizes mT5-small and BanglaT5, both trained on the "Vashantor" dataset. The dataset comprises 32,500 sentences encompassing Bangla, Banglish, and English, representing diverse regional Bangla dialects.

## Dataset

The "Vashantor" dataset used in this project can be accessed [here](https://arxiv.org/abs/2311.11142). It includes a wide range of sentence samples crucial for training and evaluation, providing a comprehensive representation of Banglish and its translation into Bangla.

## Model

The neural network models employed for translation tasks are mT5-small and BanglaT5. These transformer-based models have undergone fine-tuning on the "Vashantor" dataset, enabling efficient Banglish-to-Bangla translation.

## Evaluation Metrics

The translation models' performance is assessed using the following evaluation metrics:

- Character Error Rate (CER)
- Word Error Rate (WER)
- Exact Match
- Meteor Score
- BLEU Score
- ROUGE Score

These metrics collectively gauge the model's translation accuracy, fluency, and overall performance.



