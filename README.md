# MNIST Neural Network Activation Function Comparison

## Overview
This project implements and compares three activation functions (Sigmoid, Tanh, and ReLU) using a fully connected neural network for handwritten digit classification on the MNIST dataset.

The objective was to evaluate the impact of activation functions on training convergence, accuracy, and generalisation performance.

## Dataset
- MNIST Handwritten Digits Dataset
- 60,000 training images
- 10,000 testing images
- 28x28 grayscale images

## Model Architecture
- Input Layer: 784 neurons
- Hidden Layers: 256, 128, 64, 64, 32, 16
- Output Layer: 10 neurons (Softmax)

## Experiments Conducted
1. Sigmoid Activation
2. Tanh Activation
3. ReLU Activation

## Final Results

| Activation | Accuracy | Misclassifications |
|------------|----------|------------------- |
| Sigmoid    | 95.13%   | 487                |
| Tanh       | 97.39%   | 261                |
| ReLU       | 97.66%   | 234                |

ReLU demonstrated superior convergence and performance.

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab

## Ethical Considerations
The report discusses:
- Fairness & bias
- Transparency
- Privacy risks
- Human-in-the-loop systems

## Author
Bala Srinivas Kadali
MSc Data Science
