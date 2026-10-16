# Generative Adversarial Network (GAN)

A convolutional **Generative Adversarial Network (GAN) implemented from scratch in PyTorch**, trained to generate handwritten digits (0s and 1s) using the MNIST dataset.

## Overview

This project explores adversarial learning through two competing neural networks:

- **Generator:** Transforms random noise into handwritten digit images using convolutional layers and upsampling.
- **Discriminator:** A convolutional neural network trained to distinguish real MNIST images from generated ones.

Networks are trained adversarially, with the generator learning to produce increasingly realistic images while the discriminator learns to identify generated samples.

## Implementation

- Custom generator and discriminator architectures using PyTorch.
- Manually implemented adversarial loss functions and training loops.
- Adam optimisation and binary cross-entropy objectives.
- MNIST dataset filtered to digits 0 and 1.
- Visualisation of increasingly realistic generated images during training.


The MNIST dataset is downloaded automatically if unavailable locally. Generated samples are displayed during training using Matplotlib.

## Technologies

**Python · PyTorch · Torchvision · NumPy · Matplotlib**

## Author

[Felix Blakemore](https://github.com/13felixblakemore)
