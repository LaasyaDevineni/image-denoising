# Fashion MNIST Denoising Autoencoder

This project implements a **denoising autoencoder** using the **Fashion MNIST** dataset. A denoising autoencoder is trained to remove noise from images, improving clarity and restoring the original features. We used a **convolutional autoencoder model** built with **TensorFlow** and **Keras** to add and remove noise from grayscale images of fashion items like shirts, shoes, and bags.

## Project Overview

The denoising autoencoder model contains:
- **Encoder**: Compresses the noisy images into a latent representation.
- **Decoder**: Reconstructs the images to remove noise and approximate the original image.
- **Noise addition**: Adds random **Gaussian noise** to the images to create a noisy dataset for training.

## Requirements

- **Python 3.7+**
- **TensorFlow**: `tensorflow==2.8.0` or newer
- **NumPy**
- **Matplotlib**
- **Scikit-Learn**


3. **Download the Fashion MNIST dataset** (done automatically in the script).

## Usage

### Training the Model

The **`Autoencoder`** and **`Denoise`** models can be used for training. We used the **Fashion MNIST** dataset, adding **Gaussian noise** to create noisy versions of the images.

### Running the Code

Run the script in a **Python environment** (e.g., **Jupyter Notebook** or standard Python script):


## Install dependencies:

```
pip install tensorflow numpy matplotlib scikit-learn
```
Download the Fashion MNIST dataset (done automatically in the script).

## Training the Model
The Autoencoder and Denoise models are for training. We used the Fashion MNIST dataset, adding Gaussian noise to create noisy versions of the images.

## Evaluating Model Performance
Reconstruction: Visualize noisy and denoised images to evaluate the model's performance

## Results
The denoising autoencoder is able to effectively reduce noise, preserving the main structure of each image. Validation loss metrics are used to gauge the model’s performance over training epochs.

