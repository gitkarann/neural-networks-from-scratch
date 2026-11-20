# Neural Networks from Scratch

An exploration of fundamental neural network concepts, mathematical foundations and classical learning algorithms implemented using Python and NumPy.

This repository focuses on understanding how neural networks make predictions, calculate errors and learn from data.

## Topics Covered

### 1. Softmax Classification
- Implementing the Softmax activation function
- Converting logits into probability distributions
- Numerical stability in Softmax calculations
- Predicting class labels using weights and biases

### 2. Loss Functions
- Implementing cross-entropy loss
- Understanding one-hot encoded labels
- Comparing correct and incorrect predictions
- Numerical stability using probability clipping

### 3. MCP Neurons
- McCulloch-Pitts neuron implementation
- Building AND and OR logic gates
- Understanding threshold-based activation
- Exploring the limitations of traditional artificial neurons
- Understanding why XOR cannot be solved by a single basic MCP neuron

### 4. Perceptron Learning
- Implementing the Perceptron algorithm
- Initialising weights and biases
- Updating parameters based on classification errors
- Understanding decision functions

### 5. Binary Image Classification
- MNIST digit classification experiments
- Classifying handwritten digits 0 vs 1
- Exploring 3 vs 5 classification
- Visualising handwritten digit samples

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Repository Structure

```text
neural-networks-from-scratch/
│
├── softmax-and-cross-entropy-classification.ipynb
├── mcp-neurons-and-perceptron-learning.ipynb
└── README.md
```

## Learning Objectives

- Understand the mathematical foundations of neural networks.
- Explore how activation functions and loss functions work.
- Understand how weights and biases influence predictions.
- Implement basic learning algorithms.
- Develop a foundation for studying modern deep learning architectures.

## About

These notebooks are educational implementations designed to build a deeper understanding of neural network fundamentals and machine learning algorithms.