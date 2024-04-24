# Dependency Parser

This repository contains a Jupyter Notebook for building and training a dependency parser using neural networks.

## Features

- **Data Loading**: Load and parse dependency trees from CoNLL-U files.
- **Custom Dataset**: Implement a dataset class for handling parsing actions and transitions.
- **Neural Network Model**: Define and prepare a neural network with LSTM for predicting parser actions.

## Model

The model uses LSTM layers to process input features including word and POS tag embeddings, predicting parser actions like SHIFT, LEFT-ARC, and RIGHT-ARC.

## Usage

To use this parser, ensure you have the dataset in CoNLL-U format and adjust the paths in the notebook to point to your training and development data.

## Requirements

- PyTorch
- conllu
- gensim
- numpy
- pandas

Ensure these libraries are installed to run the notebook successfully.
