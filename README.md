# Indian Sign Language Recognition using CNN

This is a project that aims to recognize Indian Sign Language gestures using deep learning. The dataset used in this project contains 3000 images of 35 different classes. This project is based on the Convolutional Neural Network (CNN) algorithm and is built using TensorFlow and Keras. The model achieved 100% accuracy on the training set.

# Installation
This project was developed in Python3. To run this project, the following libraries must be installed:

numpy
pandas
seaborn
matplotlib
cv2
sklearn
opendatasets
tensorflow
keras

# Dataset
The dataset used in this project can be downloaded from (Kaggle)[https://www.kaggle.com/datasets/prathumarikeri/indian-sign-language-isl/]. The dataset contains 3000 images of 35 different classes. Each class represents a sign from the Indian Sign Language.

# Data Preprocessing

The dataset was preprocessed as follows:

* Images were resized to 64x64 pixels.
* Edge detection was performed on the images using the Canny Edge Detection algorithm.
* The pixel values of the images were normalized between 0 and 1.

# Model Architecture

**The model used in this project is a CNN with the following architecture:**

* Convolutional layer with 32 filters, 3x3 kernel, and ReLU activation function.
* Max pooling layer with 2x2 pool size.
* Convolutional layer with 64 filters, 3x3 kernel, and ReLU activation function.
* Max pooling layer with 2x2 pool size.
* Convolutional layer with 64 filters, 3x3 kernel, and ReLU activation function.
* Max pooling layer with 2x2 pool size.
* Flatten layer.
* Fully connected layer with 128 units and ReLU activation function.
* Fully connected layer with 35 units and softmax activation function.

# Results
The model achieved 100% accuracy on the training set and 97.5% accuracy on the test set after 10 epochs.
