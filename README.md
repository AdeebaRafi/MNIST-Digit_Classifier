MNIST Handwritten Digit Classification
Introduction

This project is a simple neural network implementation that classifies handwritten digits from the famous MNIST dataset. It serves as a great introduction to deep learning and computer vision concepts.

What I Did

Dataset Preparation: Used the MNIST dataset containing 70,000 grayscale images of handwritten digits (0-9)

Data Preprocessing:

Normalized pixel values (0-255 → 0-1)

Flattened 28x28 images into 784-pixel vectors

One-hot encoded labels

Model Architecture: Built a neural network with:

Input layer: 784 neurons (1 for each pixel)

Two hidden layers: 64 neurons each with ReLU activation

Output layer: 10 neurons with Softmax activation (1 for each digit)

Training: Used Adam optimizer and trained for 5 epochs

Evaluation: Tested the model on unseen data to measure performance

Results
Test Accuracy: Approximately 97% (may vary slightly between runs)

The model can correctly identify handwritten digits with high accuracy

Applications
This type of digit recognition technology is used in:

Postal mail sorting (reading zip codes)

Bank check processing (reading handwritten amounts)

Form processing systems

Digitizing historical documents

Any application requiring handwritten digit recognition

Note
This project was created for learning purposes to understand:

Basic neural network architecture

Image classification techniques

Deep learning workflow with Keras/TensorFlow

Model evaluation and validation

The code demonstrates fundamental deep learning concepts in a clear, accessible way, making it perfect for beginners in machine learning.

