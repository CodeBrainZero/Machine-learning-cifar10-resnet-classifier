# Machine-learning-cifar10-resnet-classifier
# CIFAR-10 Image Classification using ResNet-inspired CNN

This project implements a deep learning image classifier using a custom ResNet-inspired Convolutional Neural Network (CNN) trained on the CIFAR-10 dataset.

## Project Overview
- Dataset: CIFAR-10
- Framework: TensorFlow / Keras
- Task: Multi-class image classification (10 classes)
- Final Accuracy: ~79.8%

## Features
- Data preprocessing and normalization
- Data augmentation to reduce overfitting
- Residual connections (ResNet-style)
- Hyperparameter tuning using Keras Tuner
- Model evaluation using precision, recall, F1-score, and confusion matrix

## Model Architecture
- Convolutional layers with Batch Normalization and ReLU
- Residual blocks with skip connections
- Global Average Pooling
- Fully connected output layer with Softmax

## Installation
```bash
pip install -r requirements.txt

## Training
'''bash
python src/train.py

## Evaluation
'''bash
python src/evaluate.py
