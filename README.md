# MNIST-Classification_NN

## Problem Statement:

We need to model a NN that can predict hand written digits. (Multi- Class Classification Problem)

We are using MNIST dataset for training and evaluating the model.

## Dataset:

The MNIST dataset is imported from tensorflow_datasets library.

## Libraries used:

numpy
<br>matplotlib.pyplot
<br>seaborn
<br>tensorflow_datasets
<br>tensorflow

## Model:

**For NN model:**

Layers used: 2 Hidden Layer with relu activation.
The output layer has softmax activation.

The NN model has a good acuracy of about 98 % on test dataset without any problem of overfitting or underfitting.

**For CNN model:**

Layers used: 1 Convolution Layer, and 1 Hidden Layer with relu actiavtions.
The output layer has softmax activation.
