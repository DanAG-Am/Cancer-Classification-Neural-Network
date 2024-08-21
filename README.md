# Cancer-Classification-Neural-Network
This repository contains a machine learning project that leverages a neural network to classify cancer diagnoses based on patient data. The goal is to predict whether a given tumor is malignant or benign using a dataset of cancer features.

# Project Overview
This project implements a neural network using TensorFlow's Keras API to perform binary classification on cancer diagnosis data. The dataset includes various features extracted from cancer patient records, and the model is designed to predict whether a tumor is malignant (1) or benign (0).

## Features
# Data Preprocessing:

Normalization of feature values using StandardScaler.
Split data into training and testing sets with an 80/20 ratio.

# Model Architecture:

A sequential neural network with two hidden layers.
Each hidden layer has 256 neurons and uses the ReLU activation function.
The output layer uses the sigmoid activation function for binary classification.

# Training:

The model is trained using the Adam optimizer.
Binary cross-entropy loss function is used for training.
Includes early stopping to prevent overfitting, with patience set to 20 epochs.

# Evaluation:

The model's performance is evaluated using accuracy and loss on a separate test set.
Training and validation accuracy are plotted to visualize model performance over epochs.
