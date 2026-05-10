# Handwritten-Digit-Recognition-using-CNN-RNN
A deep learning project for handwritten digit classification using CNN and RNN models on the MNIST dataset with PyTorch. Includes data preprocessing, model training, evaluation, and performance comparison.

# Handwritten Digit Recognition using CNN & RNN

## Overview

This project focuses on handwritten digit classification using deep learning techniques with the MNIST dataset. Two neural network architectures are implemented and compared:

- Convolutional Neural Network (CNN)
- Recurrent Neural Network (RNN)

The project is built using PyTorch and demonstrates the complete deep learning workflow including data preprocessing, model creation, training, testing, and performance evaluation.

---

## Features

- MNIST handwritten digit dataset
- Data preprocessing using torchvision transforms
- CNN model implementation
- RNN model implementation
- Model training and evaluation
- Accuracy comparison between CNN and RNN
- Visualization of sample handwritten digits

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Dataset

The project uses the MNIST dataset:

- 60,000 training images
- 10,000 testing images
- 28x28 grayscale handwritten digit images
- Digits from 0 to 9

Dataset is automatically downloaded using torchvision.

---

## Project Workflow

1. Load and preprocess dataset
2. Create DataLoader for batching
3. Build CNN architecture
4. Train CNN model
5. Evaluate CNN performance
6. Build RNN architecture
7. Train RNN model
8. Evaluate RNN performance
9. Compare model accuracies

---

## CNN Architecture

The CNN model includes:

- Convolutional layers
- ReLU activation
- MaxPooling layers
- Fully connected layers
- Softmax classification through CrossEntropyLoss

---

## RNN Architecture

The RNN model includes:

- Simple RNN layer
- Hidden state learning
- Fully connected output layer
- Sequence-based image processing
