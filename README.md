# GAN_Image_Synthesis
Exploring GANs for image synthesis and data augmentation to improve CNN classification performance.

Description: 

Welcome to the GAN Image Synthesis project! This repository demonstrates the complete workflow of tackling limited dataset challenges in image classification task using Generative Adversarial Networks (GANs). 

We start by training a CNN on a small dataset, then employ a DCGAN to generate synthetic images for data augmentation. Finally, the augmented dataset is used to retrain the CNN, showing improved classification performance.

Key Highlights:

- CNN Classification: A PyTorch-based CNN was implemented as the baseline classifier. 

- GAN Image Synthesis: A DCGAN was trained to generate realistic synthetic images resembling original data. 

- Data Augmentation: Generated images were added to the dataset to mitigate data scarcity. 

- Performance Evaluation: We compare baseline CNN accuracy against CNN retrained with GAN-augmented data.

This project is a practical introduction to image synthesis, data augmentation, and deep learning architectures. Whether you’re exploring GANs, CNNs, or looking for approaches to handle small datasets, this repository provides valuable insights and hands-on implementation.
