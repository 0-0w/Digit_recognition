# Convolutional Neural Network (CNN) and Artificial Neural Network (ANN) with TensorFlow 2.x Keras API for MNIST Digit Recognition

## Overview

This Jupyter notebook demonstrates the implementation of Convolutional Neural Network (CNN) and Artificial Neural Network (ANN) using TensorFlow 2.x Keras API. The purpose of the models is to predict handwritten digits (0-9) from the MNIST dataset. The Sequential model architecture is employed to achieve accurate digit classification, with a remarkable 99.3% accuracy.

## Requirements

Make sure you have the following dependencies installed before running the notebook:

- TensorFlow 2.x
- Keras
- Jupyter notebook environment

You can install the required packages using the following commands:

```bash
pip install tensorflow
pip install jupyter
```

## Dataset

The MNIST dataset is used, which consists of 28x28 pixel grayscale images of handwritten digits (0-9). The dataset is loaded and preprocessed before training the models.

## Models

### Convolutional Neural Network (CNN)

The notebook includes the implementation of a Sequential CNN for digit recognition. The CNN architecture involves convolutional layers, pooling layers, and fully connected layers. The model is trained on the MNIST dataset to learn the patterns and features of handwritten digits.

### Artificial Neural Network (ANN)

In addition to the CNN, an Artificial Neural Network (ANN) is implemented in the notebook. The ANN is a feedforward neural network with multiple layers of neurons. It is designed to learn and classify the patterns in the MNIST dataset.

## Usage

1. Open the Jupyter notebook in your preferred environment.
2. Execute the cells sequentially to load the dataset, preprocess it, and train the CNN and ANN models.
3. Evaluate the models' performance on the test set.
4. Experiment with hyperparameters, architecture, or any other aspects to further improve the model if desired.

## Results

The trained models achieve an impressive accuracy of 99.3% on the test set, showcasing the effectiveness of both CNN and ANN architectures for digit recognition.

Feel free to explore and modify the notebook to enhance your understanding of Convolutional Neural Networks and Artificial Neural Networks using TensorFlow 2.x Keras API. If you have any questions or suggestions, please don't hesitate to reach out.

Happy coding!
