# Lung-Cancer-Detection-using-CNN
This project implements a Convolutional Neural Network (CNN) to classify lung cancer images into three
categories: benign cases, malignant cases, and normal cases. The dataset is divided into training, validation
and test sets to evaluate the model's performance.

# Project Overview
This project aims to create a reliable CNN model to predict lung cancer from CT scan images. The model classifies images
into one of three categories:
- Normal
- Benign cases
- Malignant cases

# Dataset
The dataset(IQ-OTH/NCCD) Iraq Oncology/National Center for Cancer Diseases lung cancer dataset from kaggle. It includes CT scan of patients diagnosed with lung cancer in different stages, as well as healthy subjects. The dataset contains a 1190 images including normal, benign, and malignant cases.

# Installation
To run this project, you will need to install the following dependencies:
![image](https://github.com/Ohmdatazwld5/Lung-Cancer-Detection-using-CNN/assets/130119515/235ef3b0-b21f-4111-b2e7-3c7d10635e9c)

# Usage
# 1. Prepare the dataset:
Place your dataset in the "Lung_cancer_dataset" directory with the following structure
![image](https://github.com/Ohmdatazwld5/Lung-Cancer-Detection-using-CNN/assets/130119515/00590f36-200d-4e3e-a406-c621220fd2bc)

# Model Architecture
The CNN model is built using Keras and TensorFlow, with the following layers:
- Convolutional Layers: Extract features from images.
- Max Pooling Layers: Downsample the spatial dimensions.
- Fully Connected Layers: Perform classification based on the extracted features.
- Activation Functions: ReLU for hidden layers and Softmax for the output layer.

# Training and Validation
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Metrics: Accuracy
- Callbacks: EarlyStopping and overfitting
The model is trained for 50 epochs with early stopping based on validation loss

# Results
- Final Training Accuracy: 99.77%
- Final Validation Accuracy: 97.92%

# Ouput Visualiazation
![image](https://github.com/Ohmdatazwld5/Lung-Cancer-Detection-using-CNN/assets/130119515/63158dc3-7f64-46f3-8d4b-7086c1df549e)
![image](https://github.com/Ohmdatazwld5/Lung-Cancer-Detection-using-CNN/assets/130119515/8fa3f57f-f887-4dd8-a67d-717064495865)

# Acknowledgements
- The Keras and TensorFlow libraries provide powerful tools to build and train neural networks

Feel free to customize this README further to better fit your specific project details or personal preferences.

