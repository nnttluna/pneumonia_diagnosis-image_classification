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

# Resutls

The image classification using a convolutional keras neural
network proved to perform extremely well, with an accuracy of 97% and about equal numbers of
false positives and false negatives. The first challenge pertained to the initial size of the images.
Working through errors in our code it was soon noticed that the imported images were all of
different sizes. By resizing all images to have the same amount of pixels we were able to
resolve this issue, as well as make it easier for the network to learn. Once we had a working
model it was important to have a visualization of the point where the model would overfit.
Graphically representing the loss of training and validation data enabled a better estimate of the
amount of epochs needed. Through trial and error an epoch of 15 proved to provide high
accuracy without overfitting the data.
