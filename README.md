
# Deep Learning Assignment: Generative Models and Sequence Arithmetic

## About This Project

This repository contains work completed for Assignment 2 of the Introduction to Deep Learning course. The project explores two fundamental areas of deep learning:

1.  **Generative Modeling:** Investigating the ability of models like Variational Autoencoders (VAEs) and Generative Adversarial Networks (GANs) to learn underlying data distributions and generate novel, realistic images.
2.  **Sequence Modeling:** Utilizing Recurrent Neural Networks (specifically LSTMs) within an encoder-decoder framework to learn and perform tasks based on sequential data, focusing on simple arithmetic operations.

## Overview

The project involved implementing, training, and evaluating deep learning models for these two core tasks:

### 1. Generative Image Models

*   **Goal:** Generate novel images of cats using VAEs and GANs, comparing their performance against a baseline Convolutional Autoencoder (CAE).
*   **Dataset:** A curated dataset of ~30,000 cat images (75x75 pixels).
*   **Outcome:** Successfully trained models capable of generating new images. GANs produced diverse outputs, while VAEs demonstrated good generalization capabilities by learning latent distributions. Experiments included analyzing latent spaces and sampling strategies.

### 2. Sequence Modeling for Arithmetic

*   **Goal:** Train LSTM-based encoder-decoder models to perform simple addition and subtraction on two-digit numbers (e.g., `45+23=68`).
*   **Tasks & Modalities:**
    *   **Text-to-Text:** Inputting and outputting arithmetic problems as text strings.
    *   **Image-to-Text:** Inputting problems as sequences of character images and outputting the result as text.
    *   **Text-to-Image:** Inputting problems as text and outputting the result as a sequence of character images.
*   **Outcome:** Demonstrated that RNNs can learn basic arithmetic rules across different data formats (text and images), achieving high accuracy on seen and unseen examples, particularly for text-based tasks. Explored architectural variations (e.g., adding LSTM layers) to improve performance.

## Technologies Used

*   Python
*   TensorFlow / Keras
*   NumPy
*   OpenCV (for image preprocessing)
*   Scikit-learn (for evaluation)
*   Matplotlib / Seaborn (for visualization in notebooks)

## Explore the Code

Detailed implementations, experiments, training logs, and visualizations for each model and task can be found in the Jupyter notebooks within this repository (e.g., `VAE.ipynb`, `GAN.ipynb`, notebooks for sequence tasks).
