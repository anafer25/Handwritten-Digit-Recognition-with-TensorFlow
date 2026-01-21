## MNIST Handwritten Digit Recognition with TensorFlow

# Overview
This project demonstrates how to build and train a neural network using TensorFlow to recognize handwritten digits (0–9) from the MNIST dataset. The goal of the project is to practice core machine learning concepts such as model building, training, evaluation, and prediction visualization using Python.

The model was implemented and trained in Google Colab, leveraging free CPU/GPU resources for faster experimentation.

# Dataset

MNIST (Modified National Institute of Standards and Technology) is a standard benchmark dataset in machine learning.
* 70,000 grayscale images of handwritten digits
* Image size: 28 × 28 pixels
* 60,000 training images
* 10,000 test images

Each image represents a digit from 0 to 9.

# What Is a Neural Network?

A neural network is a machine learning model inspired by the human brain. It consists of layers of interconnected nodes (“neurons”) that learn patterns in data.

In this project, the neural network learns patterns in pixel values that correspond to handwritten digits.

# What I did:
* Loaded the MNIST dataset using TensorFlow
* Normalized pixel values to improve training performance
* Built a neural network using Keras layers
* Compiled the model by defining:
  * Optimizer (how the model updates weights)
  * Loss function (how prediction errors are measured)
  * Accuracy metric
* Trained the model using TensorFlow’s built-in training loop
* Evaluated performance on unseen test data
* Visualized predictions to confirm correct digit classification

# Training Loop

The training loop is handled automatically by TensorFlow using model.fit().
During training:
1. The model makes predictions
2. The loss is calculated
3. Weights are adjusted to reduce errors
4. This process repeats over multiple epochs

# Results

Test accuracy of approximately 97–98% using a simple dense neural network
Correct predictions visualized for sample handwritten digits

# Tools & Technologies

Python
TensorFlow / Keras
Google Colab
Matplotlib

# Future Improvements

Replace dense layers with a Convolutional Neural Network (CNN)
Improve accuracy beyond 99%
Add real-time digit recognition using a webcam
Experiment with different optimizers and activation functions

# License

This project is licensed under the MIT License.

# Acknowledgments

MNIST Dataset

TensorFlow Documentation
