# ADC2021: Unsupervised New Physics detection at 40 MHz

**NOTE:**
* This repository is a fork of the original [AD Challenge 2021 Example code](https://github.com/mpp-hep/ADC2021-examplecode)
* We will using this repo for our development. You can develop your code on a different branch of this repo.


-----

This repository contains code examples for analysing the [Anomaly Detection
Data Challenge](https://mpp-hep.github.io/ADC2021/) datasets.

In this repository you will find code examples for the following:

1. How to load background dataset
2. Examples of define model architectures for anomaly detection
3. How to train the model
4. Compute the model predictions on background data
5. Compute the model predictions on signal (anomalies)
6. Evaluate model's performance using 2 different techniques
7. Evaluate the number of floating point operations of the model

This information can be found in scripts:

1. **Convolutional_AE.ipynb**: Load the data, define a convolutional autoencoder and evaluate it's performance
2. **Dense_AE.ipynb.ipynb**: Load the data, define a fully connected dense autoencoder and evaluate it's performance
3. **graph_vae.ipynb**: Define a graph autoencoder or graph variational autoencoder
4. **computeFLOPs.ipynb**: Compute the number of floating point operations for a given model
5. **create_datasets.py**: Create datasets for training/validation/testing in the HDF5 format.



