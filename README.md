# TCC_II
This repository contains the main Colab Notebooks used in my Final Work. 

The object of study is the AutoML (Automated Machine Learning) and the focus is on the Hyperparameter Search, using the library Keras Tuner.

Introduction to the Keras Tuner: [Colab Notebook](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/keras/keras_tuner.ipynb)

My adapted notebooks were named according to their characteristics:
* kt / keras_tuner: implements the [Keras Tuner library](https://keras.io/keras_tuner/) (all notebooks here use it)
* BO: the HP serach implements the Bayesian Optimization method (all notebooks here use it)
* MNIST: implements the [MNIST dataset](https://keras.io/api/datasets/mnist/)
* fashMNIST: implements the [Fashion MNIST dataset](https://keras.io/api/datasets/fashion_mnist/)
* CNN: implements a Convolutional Neural Network with a model much larger than the non-CNN notebooks
* custom_loss / chebloss: implements a customized loss function based on Chebyshev scalarizing 
