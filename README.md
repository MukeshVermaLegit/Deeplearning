Overview
This project demonstrates a machine learning pipeline for classifying MRI images into two categories: Normal and Dementia. It employs a Convolutional Neural Network (CNN) model built using TensorFlow and Keras to analyze grayscale image data. The pipeline includes dataset preprocessing, model training, and evaluation.

Features:
Preprocessing: Resizes images to 100x100 pixels, converts them to grayscale, and normalizes pixel values.
Dataset Split: Splits data into training and testing sets (80:20).
CNN Architecture:
Convolutional Layers with ReLU activation
MaxPooling Layers
Dense Layers with Softmax activation for classification
Performance Visualization: Plots training/validation accuracy and loss across epochs.
Evaluation: Outputs accuracy and loss metrics on the test dataset.
