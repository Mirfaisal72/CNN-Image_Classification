# CNN Image Classification: Dog vs Cat
This repository contains a Convolutional Neural Network (CNN) implementation for image classification of dogs and cats using the TensorFlow and Keras libraries. The CNN model is trained to differentiate between images of dogs and cats.

# Table of Contents
Introduction
Dataset
Training the Model
Evaluation
Making Predictions
# Introduction
Convolutional Neural Networks (CNNs) are a class of deep learning models particularly well-suited for image classification tasks. In this project, we use a CNN to classify images of dogs and cats.

# Dataset
The dataset for this project consists of images of dogs and cats. The dataset is divided into training and testing sets. Each image is represented as a matrix of pixel values in the Red, Green, Blue (RGB) color channels.

# Training the Model
The CNN model architecture for image classification is defined using the Keras Sequential API. The architecture includes Convolutional and MaxPooling layers followed by fully connected Dense layers. The model is compiled with an Adam optimizer and binary cross-entropy loss function.

# Evaluation
After training, the model is evaluated on the testing dataset. The test loss and accuracy are calculated using the trained model.

# Making Predictions
You can use the trained model to make predictions on new images. A random test image is selected, and its predicted class label (dog or cat) is displayed.



