# Generating High-Fidelity Brain Tumor Images with Deep Convolutional GANs

## Overview

This project addresses the challenge of limited brain tumor imaging datasets by leveraging **Deep Convolutional Generative Adversarial Networks (DCGANs)**. The goal is to generate high-quality synthetic brain tumor images for dataset augmentation, enhancing the training of machine learning models in medical imaging.

---

## Features

- **Synthetic Image Generation**: Creates realistic brain tumor images using DCGANs.
- **Optimized Hyperparameters**: Tuned for noise dimension, batch size, and steps per epoch.
- **Performance Metrics**:
  - **Generator Loss**: 2.4969
  - **Discriminator Loss**: 0.0436
- **Discriminator Functionality**: Differentiates between real and generated images to improve overall performance.

---

## Dataset

- **Type**: Grayscale images of brain tumors.
- **Purpose**: Provides input for training the DCGAN model.

---

## Methodology

1. **DCGAN Architecture**:
   - **Generator**: Converts noise into synthetic brain tumor images.
   - **Discriminator**: Differentiates between real and synthetic images, enhancing generator learning via adversarial training.

2. **Optimization**:
   - **Noise Dimension**: Configured for diverse synthetic image generation.
   - **Batch Size**: Balanced for training speed and accuracy.
   - **Steps per Epoch**: Optimized for effective training.

---

## Results

- **Generator Loss**: 2.4969
- **Discriminator Loss**: 0.0436

---

## Requirements

Install the following Python libraries:
- TensorFlow/Keras
- NumPy
- OpenCV
- Matplotlib

---

## Installation

1. Clone this repository:
   git clone https://github.com/your-repo-url.git

2. Navigate to project directory:
   cd your-project-directory

3. Install the required dependencies:
   pip install -r requirements.txt

