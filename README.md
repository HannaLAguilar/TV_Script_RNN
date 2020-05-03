# TV Script with RNN

## Project overview

This project implements a recurrent neural network (LSTM) for training a language model. This model is used to generate a new text, based on the patterns it learned from the training data.

The dataset was composed of scripts from the Seinfeld TV show.

The project involves:

* Text processing: normalize and cleaning text
* Train the model: LSTM neural network
* Generate new script

### Hyperparameters

A import task in the project is to set the hyperparameters. The two most important parameters that control the model are hidden_dim and n_layers. The `n_layers` usually takes a number between 2 or 3, in this project I set it as 2.

If you want to improve the model, you can tweak these parameters:

- epoch = 5
- learning_rate = 0.001
- sequence_length = 200
- batch_size = 50
- embedding_dim = 400
- hidden_dim = 256
- n_layers = 2

### Technologies used:

* Python, numpy
* Neural networks 
* RNN, LSTM
* jupyter notebook, anaconda

## Installation

Using [Anaconda](https://www.anaconda.com/products/individual), in an enviroment with python 3, install the following packages:
```
conda install jupyter, numpy, 
conda install -c pytorch pytorch
```
