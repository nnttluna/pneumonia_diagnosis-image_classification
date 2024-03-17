# Pneumonia-Detection-from-X-Rays

# Creating ML algorithm for Pneumonia Detection 

We will develop a computer vision model to detect pneumonia in histopathological images, assisting in diagnosis. Two classes will be used in this project: **Positive or Negative.**

# Data Analysis Hypothesis: 

From the convolutional keras neural network, we expect favourable results due to
this model's nature of processing 2D images. This model includes combining convolutional
layers, reLU layers as well as a fully connected layer. As each layer increases with different
learned features from the images, the CNN model should accurately provide the classification of our
dataset without many preprocessing functions. This model compared to normal neural networks
is advantageous due to this model being able to work in a 2D plane and this will in result help
retain the spatial properties of the input image. As we increase the number of epochs within this
model as well as convolution layers, the model will be able to train and learn the input images
yielding improved accuracy (>90%) in predicting and testing compared to other deep learning
models for images.

# Instructions

The project is broken down into multiple steps:

    Load and preprocess the image dataset
    Train the image classifier on your dataset
    Use the trained classifier to predict image content

Everything you need to recreate this project is on the jupyter notebook. Everything was coded in Google Colab, because of its GPU. The dataset was uploaded to Google Drive, so you can download it directly (the code to download it is in the notebook). For more details, the notebook includes the instructions to follow.

This project is updated to be compatible with PyTorch 0.4.0
