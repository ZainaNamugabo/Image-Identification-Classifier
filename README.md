# Image-Identification-Classifier
This repository contains a deep learning model for classifying images of clothing items into 10 different categories. The model is built using TensorFlow and Keras and is trained on the Fashion MNIST dataset

Model Architecture
The model is a convolutional neural network (CNN) with the following architecture:

Conv2D Layer: 8 filters, kernel size of 3x3, ReLU activation
MaxPooling2D Layer: 2x2 pool size
Flatten Layer
Dense Layer: 10 output units, softmax activation
Dataset
The model is trained on the Fashion MNIST dataset, which consists of 60,000 28x28 grayscale images of 10 different clothing categories.

Usage
To use the model, you will need to have TensorFlow and Keras installed. You can then load the trained model and use it to predict the class of a new image. See the included notebook for an example of how to do this.
