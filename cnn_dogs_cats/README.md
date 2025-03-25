# CNN for Dogs vs Cats Kaggle competition

## Description
this project have been developed as part of a self though learning path of deep leraning. In this project have been used Keras API and tensor flow to develop a CNN to clasify a images of dogs and cats. This project use dataset from Dogs vs cat of kaggle competition: For reference: https://www.kaggle.com/c/dogs-vs-cats/data

## Dataset
This project uses dataset from Dogs vs cats of kaggle competition, a collection of 20000 RGB images with different shapes. The notebook organize_data.ipynb is used to separate the data into train (80%) and validation (20%). Also the notebook separate dogs and cats image in diferent directories. The main notebook dogs_vs_cats.ipynb use data augmentation techniques to improve the training process.

## Model
This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify Fashion MNIST images.

## Requirements
Ensure you have the following Python libraries installed:
- matplotlib
- numpy
- sklearn
- tensorflow

You can install missing dependencies using:
```bash
pip install -r requirements.txt
```

## Usage
Run the following command to execute the notebook:
```bash
jupyter notebook dogs_vs_cats.ipynb
```

## Results
The model has an accuracy of 88.24% in training dataset, 90.26% in validation dataset.
![TRAINING AND VALIDATION](LINK)

## Sample Results
![Result 1](image_0.png)