# Automated Pneumonia Detection from Chest X-Ray Images

## Project Overview
This project focuses on automated detection of pneumonia from chest X-ray images using a Convolutional Neural Network (CNN) built entirely from scratch. The goal is to assist in early diagnosis while following strict academic guidelines.
## Project Objectives

The main objectives of this project are:
- To design and implement a Convolutional Neural Network (CNN) from scratch for pneumonia detection.
- To preprocess and normalize chest X-ray images for effective learning.
- To train and evaluate the model using clinically relevant metrics.
- To develop a reliable inference mechanism for classifying new chest X-ray images.
- To understand the complete deep learning pipeline including training, evaluation, and inference.
## Domain
Healthcare / Medical Imaging

## SDG Alignment
SDG 3 – Good Health and Well-Being

## Key Highlights
- CNN model implemented from scratch
- No pretrained models used
- Focus on data preprocessing, training, inference, and evaluation
- Clinically relevant evaluation metrics (Precision, Recall, F1-score)

## Dataset
- Source: Kaggle (Chest X-Ray Pneumonia Dataset)
- Classes: Normal, Pneumonia
- Total images used: 800
- Stratified train, validation, and test split

## Tools & Technologies
- Python
- TensorFlow / Keras
- NumPy, Matplotlib, Scikit-learn
- Google Colab

## Project Status
Initial repository setup completed.
## Results Summary

The CNN model was trained on a balanced dataset of 800 chest X-ray images (400 Normal, 400 Pneumonia).

### Performance Metrics
- Accuracy: 95%
- Precision (Pneumonia): 0.93
- Recall (Pneumonia): 0.98
- F1-score: 0.95

The confusion matrix shows a low number of false negatives, which is critical for medical diagnosis.

### Evaluation
- Training vs validation accuracy and loss curves indicate stable convergence.
- No severe overfitting was observed.
- Evaluation results and plots are available in the `results/` folder.


