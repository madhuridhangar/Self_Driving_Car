# Self_Driving_Car

## A simple end- to -end autopilot system that takes front camera view as input and predict the steering angle.

Dataset : https://github.com/SullyChen/Autopilot-TensorFlow

This model uses a simple CNN model :

The first layer of the network performs image normalization.
The convolutional layers are designed to perform feature extraction.
Uses a strided convolutions in the first three convolutional layers with a 2×2 stride and a 5×5 kernel,
And a non-strided convolution with a 3×3 kernel size in the final two convolutional layers.
Followa the five convolutional layers with three fully connected layers, leading to a final output control value which is the inverse-turning-radius
The fully connected layers are designed to function as a controller for steering

Refer: https://arxiv.org/pdf/1604.07316.pdf
