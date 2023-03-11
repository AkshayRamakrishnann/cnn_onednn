# Simple CNN implementation using oneAPI

![cfdffc801cd0702b300316d228cd55e1_e57a034e8cc411eb88ae0e1f58d5e9a9_0_cover-MNIST](https://user-images.githubusercontent.com/111365771/224469399-87010676-eb1a-4bff-9c73-35a59443e9ba.png)


## Introduction
This is a simple project using OneDNN to train a convolutional neural network (CNN) on the MNIST dataset. The goal of this project is to demonstrate how to use OneDNN to accelerate training of neural networks.

## About the Dataset
The MNIST dataset is a collection of 60,000 training images and 10,000 testing images of handwritten digits. Each image is a grayscale 28x28 pixel image, and the goal is to correctly classify which digit is represented in each image.

## Models Used
In this project, we use a simple CNN architecture consisting of a single convolutional layer with 32 filters, followed by a max pooling layer, a flattening layer, and a dense output layer with 10 units and softmax activation.

## OneAPI and OneDNN
OneAPI is a set of open standards and specifications for heterogeneous computing. OneDNN is a software library developed by Intel for accelerating deep learning workloads using CPU, GPU, and other accelerator hardware.

## Methods and Materials
We implemented the CNN model using TensorFlow and trained it using the OneDNN backend. We used the Adam optimizer and sparse categorical crossentropy loss function. The model was trained for 5 epochs on the training set, and the test set was used to evaluate the final accuracy of the model.

## Results
After training the model, we achieved a test accuracy of 98.20%. The training and validation accuracy and loss were visualized using matplotlib and are shown below:

![download (3)](https://user-images.githubusercontent.com/111365771/224469402-38b9bb4b-f679-46c1-87c4-c40dc56e6955.png)


Training and Validation Accuracy and Training and Validation Loss


## Conclusion
In this project, we demonstrated how to use OneDNN to accelerate training of a CNN on the MNIST dataset. The resulting model achieved high accuracy on the test set and can be used as a baseline for further experimentation.
