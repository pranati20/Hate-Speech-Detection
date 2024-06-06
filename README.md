# Hate Speech Detection

This project focuses on detecting hate speech in text using machine learning techniques. The dataset used for training and testing the models was obtained from Kaggle: [Multimodal Hate Speech Dataset](https://www.kaggle.com/datasets/victorcallejasf/multimodal-hate-speech).

## Project Overview

The project consists of two main notebooks:

1. **mmhs150k.ipynb**: This notebook contains the data understanding, preprocessing, and model training process. It utilizes natural language processing techniques such as tokenization and leverages libraries like NLTK. Additionally, a BERT model is replicated using Python libraries like tensorflow, and fine-tuned for hate speech detection.

2. **spotfake.ipynb**: In this notebook, the trained model from `mmhs150k.ipynb` is utilized for detecting hate speech in text. It includes tokenization and model evaluation steps.

## Dataset

The [Multimodal Hate Speech Dataset](https://www.kaggle.com/datasets/victorcallejasf/multimodal-hate-speech) consists of text data annotated for hate speech, making it suitable for training machine learning models for hate speech detection tasks.

## Results

After training and testing the model, it achieved an accuracy of 93% in detecting hate speech.



