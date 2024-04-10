# Convolutional Neural Network (CNN) Project on CIFAR-10 Dataset
## Overview:

This project is an implementation of a Convolutional Neural Network (CNN) for image classification using the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The classes include airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

## Project Structure:
- cifar10_cnn_model.ipynb: Jupyter notebook containing the implementation of the CNN model.
- cifar10_data_preprocessing.ipynb: Jupyter notebook for data preprocessing and exploration.
- cifar_10_cnn_model.py: Python script version of the CNN model implementation.
- requirements.txt: File containing all the required libraries and their versions for easy reproduction of the environment.
## Model Architecture:

The CNN model architecture used for this project consists of multiple convolutional layers followed by max-pooling layers, and fully connected layers. The details of the model architecture, including the number of layers, activation functions, and optimizer, can be found in the cifar10_cnn_model.ipynb file.

### Data Preprocessing:
The cifar10_data_preprocessing.ipynb notebook contains the steps for data preprocessing and exploration. This includes data loading, normalization, visualization of the dataset, and data augmentation techniques if applied.

## Results:
The model was trained on a subset of the CIFAR-10 dataset and evaluated on a separate test set. The results, such as training accuracy, validation accuracy, and test accuracy, are presented in the cifar10_cnn_model.ipynb file.

## How to Run:
To reproduce the results of this project, follow these steps:

- Clone the repository to your local machine.
- Install the required libraries using the requirements.txt file.
- Run the notebooks/scripts in the following order:
- cifar10_data_preprocessing.ipynb: For data preprocessing and exploration.
- cifar10_cnn_model.ipynb: For training and evaluation of the CNN model.

## Contact:
For any questions or feedback, feel free to contact the project owner at @parthagunturu2003@gmail.com