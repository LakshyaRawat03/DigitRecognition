# Digit Recognition with Neural Network from Scratch

This project implements a simple neural network **from scratch (no deep learning libraries)** to recognize handwritten digits from the **MNIST dataset**. It demonstrates the core principles behind how neural networks learn and make predictions.

## Dataset

The model is trained on the **MNIST dataset**, which contains 70,000 grayscale images of handwritten digits (0–9):

- **60,000 training images**
- **10,000 testing images**
- Each image is **28x28 pixels** (flattened into 784 features)

Dataset source: [MNIST - Yann LeCun](http://yann.lecun.com/exdb/mnist/)

## Features

- Fully connected neural network implemented from scratch using **NumPy**
- No use of deep learning frameworks (e.g., TensorFlow, PyTorch)
- Forward propagation and backpropagation manually implemented
- Trained with stochastic gradient descent
- Supports single hidden layer (can be extended)

## How It Works

1. Load and normalize MNIST images
2. Initialize network parameters (weights and biases)
3. Forward propagate input to compute output predictions
4. Compute loss using cross-entropy
5. Backpropagate error to update weights
6. Repeat for several epochs to minimize loss

## Network Architecture

- **Input layer**: 784 neurons (28x28 pixels)
- **Hidden layer**: 10 neurons (configurable)
- **Output layer**: 10 neurons (for digits 0–9)
- **Activation**: ReLU (hidden), Softmax (output)

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/digit-recognition-nn.git
cd digit-recognition-nn
