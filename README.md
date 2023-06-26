# CIFAR-10 Image Classification
This repository contains a machine learning model designed to classify images from the CIFAR-10 dataset into one of 10 classes.

## Dataset Overview
The CIFAR-10 dataset consists of 60,000 32x32 color images evenly distributed across 10 classes, with 6,000 images per class. The classes are airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

The dataset is divided into 50,000 training images and 10,000 testing images. The training images are further split into 5 batches of 10,000 images each. The test set contains exactly 1,000 randomly-selected images from each class.

## Model Architecture
The model consists of two main parts: a backbone and a classifier. The backbone comprises several blocks, each of which contains multiple convolutional layers. The classifier is a fully connected layer that takes the output from the backbone and makes the final prediction.

## Usage
This project can be used to classify images from the CIFAR-10 dataset. The model takes as input a 32x32 color image and outputs the predicted class for that image.
