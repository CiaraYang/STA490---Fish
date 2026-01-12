# STA490---Fish_Classification

## Overview

The Fish Species Classification project investigates whether wideband acoustic signals can be used to reliably distinguish fish species, with a focus on classifying alewife and rainbow smelt. The analysis uses wideband acoustic recordings collected from [data source to be specified].

The project integrates data preprocessing, feature representation, and neural network modeling to analyze the spectral and temporal characteristics of acoustic signals. One-dimensional (1D) structured neural networks—including deep neural networks (DNNs), convolutional neural networks (CNNs), and residual networks (ResNet)—were applied to preserve the sequential structure of the data. In addition, recurrent neural networks (RNNs) were explored as a complementary approach to explicitly model temporal dependencies in acoustic sequences.

Model performance was evaluated using validation-based metrics, and the most suitable model was selected based on overall predictive accuracy and generalization performance on a held-out test set. By identifying effective modeling strategies for acoustic-based fish classification, this project demonstrates the potential of non-invasive monitoring methods for ecological research and fisheries management.

## File Structure

| Folder / File | Description |
|--------------|-------------|
| [`Data`](Data/) | Processed and raw hydroacoustic datasets |
| [`EDA`](EDA/) | Data Exploratory Analysis |
| [`Recurrent_Neural_Network`](Recurrent_Neural_Network/) | RNN models and training scripts |
| [`Resources`](Resources/) | External repositories and additional resources |
| [`README.md`](README.md) | Project documentation |

