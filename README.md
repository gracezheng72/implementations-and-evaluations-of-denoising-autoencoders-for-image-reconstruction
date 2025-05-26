# implementations-and-evaluations-of-denoising-autoencoders-for-image-reconstruction
# Denoising Autoencoder (CS 271 HW2 - Question 3)

This repository contains implementations and evaluations of denoising autoencoders for image reconstruction in the topics in Machine Learning.

## Overview

Implementing and comparing:

- **Basic Denoising Autoencoder (DAE)** using fully connected layers.
- **Convolutional Autoencoder (CAE)** for improved image denoising.
- **Image Colorization with CAE** applied to grayscale inputs.

All experiments are conducted on the MNIST dataset, with added Gaussian noise for denoising tasks.

## Tasks

- **(a)** Train a basic autoencoder for denoising images.
- **(b)** Test the model on noisy MNIST test images and visualize denoised outputs.
- **(c)** Replace dense layers with convolutional layers and retrain (CAE).
- **(d)** Use the CAE to colorize grayscale frames from a video or historical images.

## Requirements

- Python 3.8+
- PyTorch
- torchvision
- matplotlib
- numpy

Install dependencies via:

```bash
pip install torch torchvision matplotlib numpy
