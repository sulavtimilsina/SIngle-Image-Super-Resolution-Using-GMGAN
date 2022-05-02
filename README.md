# Single-image-super-resolution
Reconstruct a high-resolution (HR) image from a low-resolution (LR) using GM-GAN

## Introduction
SISR(Single Image Super-Resolution) is an application of GAN. Image super-resolution is the process of enlarging small photos while maintaining a high level of quality, or of restoring high-resolution images from low-resolution photographs with rich information. Here the model’s work is to map the function from low-resolution image data to its high-resolution image. Instead of giving a random noise to the Generator, a low-resolution image is fed into it. After passing through various Convolutional Layers and Upsampling Layers, the Generator gives a high-resolution image output. Generally, there are multiple solutions to this problem, so it’s quite difficult to master the output up to original images in terms of richness and quality.

In this study, I used Wasserstein GAN with Gradient Penalty to train SRGAN, ensuring steady training of both generator and discriminator. Please visit this article where I have explained each and every single thing that are crucial from data processing to training: https://gautammilan.github.io/post/single-image-super-resolution/
