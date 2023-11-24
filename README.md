# Digits-Recognition-With-MNIST-And-CNN
This repository contains a simple implementation of MNIST digit classification using TensorFlow 2.0. The MNIST dataset consists of 28x28 pixel grayscale images of handwritten digits (0 through 9), and the goal is to train a neural network to accurately classify these digits.  
The model architecture consists of a flatten layer followed by two dense layers with ReLU activation and a final output layer with softmax activation.  
Stochastic Gradient Descent (SGD) is used as the optimizer, and sparse categorical crossentropy is used as the loss function.  
The training is performed for 10 epochs with a batch size of 32.  
