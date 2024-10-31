# Malaria Detection using TensorFlow

This project uses a Convolutional Neural Network (CNN) implemented in TensorFlow to classify images as malaria-infected or uninfected. The model is trained on a dataset of cell images, using layers like Conv2D, MaxPooling, and Dense for image classification.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Malaria is a life-threatening disease transmitted by mosquitoes. Detecting malaria using image processing techniques can assist in early diagnosis. This project uses a deep learning approach to automate the detection of malaria from cell images.

## Dataset
The dataset is obtained from the **TensorFlow Datasets** library and contains labeled cell images for malaria-infected and uninfected cells.

## Model Architecture
The model is built using the following layers:
- **Input Layer**: Accepts input images.
- **Conv2D**: Convolution layers for feature extraction.
- **MaxPooling**: Reduces the dimensionality of the feature maps.
- **BatchNormalization**: Normalizes activations to improve performance.
- **Dense**: Fully connected layers for classification.

### Loss Function
The model uses **Binary Cross-Entropy** as the loss function.

### Optimizer
**Adam** optimizer is used for training the model.
