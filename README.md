# Neural Network from Scratch for Digit Classification

## Overview

This project implements a **feedforward neural network from scratch** to classify handwritten digits.  
The goal of the project is to understand the core mechanics of neural networks without relying heavily on high-level deep learning libraries.

The implementation demonstrates the fundamental components of a neural network including:

- Forward propagation
- Backpropagation
- Gradient-based optimization
- Multi-layer architecture
- Model training and evaluation

This project focuses on building an intuitive understanding of neural network learning dynamics.

---

## Dataset

The model is trained on a dataset of handwritten digits similar to the **MNIST dataset**.

Each sample consists of:

- A **28 × 28 grayscale image**
- A corresponding **digit label (0–9)**

The images are flattened into vectors before being passed through the neural network.

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

This implementation emphasizes **manual implementation of neural network operations** using NumPy.

---

## Model Architecture

The neural network follows a **fully connected feedforward architecture** consisting of:

Input Layer  
Hidden Layers  
Output Layer

Key components implemented:

- Weight initialization
- Activation functions
- Forward propagation
- Backpropagation
- Gradient descent optimization

The output layer uses **Softmax activation** for multi-class classification.

---

## Training Process

The model is trained using **gradient descent optimization**.

Key steps include:

1. Forward propagation to compute predictions
2. Loss calculation
3. Backpropagation to compute gradients
4. Weight updates using gradient descent

Training is performed for multiple epochs to minimize classification error.

---

## Results

The neural network successfully learns to classify handwritten digits by extracting patterns from the input images.

The training process demonstrates how model accuracy improves as the network learns optimal weight parameters.

---
