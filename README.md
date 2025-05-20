# Generative-Adversarial-Network

Plastic Pellet Contamination Analysis Using GAN

Overview

This project focuses on analyzing plastic pellet raw materials for contamination detection. Due to limited availability of real-world images, a Generative Adversarial Network (GAN) is implemented to generate synthetic images of plastic pellets. These generated images are used to augment the dataset for training downstream machine learning models to detect contamination.

The code uses TensorFlow and Keras to build and train a vanilla GAN, generating high-resolution images (800x600 pixels) that mimic real plastic pellet samples. The GAN consists of a generator and a discriminator, with configurable architectures to balance memory usage and model complexity.


Features
* Custom GAN Implementation: A flexible GAN model with generator and discriminator networks tailored for generating 800x600 RGB images.
* Configurable Memory Usage: Options (REDUCE_MEM) to adjust model size for different computational environments (e.g., PC, Colab).
* Dataset Handling: Supports custom image datasets (MYIMAGE) and includes preprocessing for training.
* Model Saving: Option to save trained generator and discriminator models for reuse.
* Image Generation: Generates synthetic images stored in the dst_img directory for further analysis or model training.

Requirements
* Python 3.8+
* TensorFlow 2.x
* NumPy
* Matplotlib
* Keras
