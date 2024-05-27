# Aircraft-Recognition
Welcome to the project! This repository is a work in progress and contains the initial code and resources for detecting and recognizing aircraft in satellite imagery using Convolutional Neural Networks (CNNs).


## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Input Images](#input-images)
- [Model Architecture](#model-architecture)
- [Image Data Generation](#image-data-generation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Dataset Preparation](#dataset-preparation)

## Introduction
This project aims to leverage the power of CNNs to accurately identify and classify aircraft in satellite images. By training a deep learning model on a labeled dataset of satellite imagery, we hope to automate the process of aircraft detection, which has applications in surveillance, military operations, and air traffic management.

## Features
- **Accurate Detection:** Utilizes CNNs for high accuracy in aircraft detection.
- **Scalable:** Designed to process large satellite images for real-time recognition.
- **User-friendly Interface:** Simple commands for running detection on new images.

## Real World Application
- **Surveillance:** Automatically detecting and identifying aircraft in satellite images for monitoring and security purposes.
- **Military Operations:** Enhancing reconnaissance capabilities by identifying aircraft in satellite imagery, aiding in strategic planning and threat assessment.
- **Air Traffic Management:** Assisting in the monitoring of air traffic by providing real-time data on aircraft positions and types.
- **Environmental Studies:** Analyzing air traffic patterns to study their impact on the environment and urban areas.

## Input Images
Images Captured from google earth for military aircraft

<img width="420" alt="Screenshot 2024-05-27 at 6 01 33 PM" src="https://github.com/Prateek-Main/Aircraft-Recognition/assets/114331206/4e486837-a0f0-45de-a8e2-081ff21bf7e1">

## Predictions and EDA
The images are sorted with the aircraft names


<img width="541" alt="Screenshot 2024-05-27 at 6 03 14 PM" src="https://github.com/Prateek-Main/Aircraft-Recognition/assets/114331206/5503ebce-62ac-43d7-9272-d3928332ef02">
<img width="536" alt="Screenshot 2024-05-27 at 6 02 57 PM" src="https://github.com/Prateek-Main/Aircraft-Recognition/assets/114331206/db963373-f09a-4c4b-9b2c-17a40c2580d3">

## Model Architecture

The CNN architecture used in this project is based on a pre-trained model fine-tuned for aircraft detection. The network includes several convolutional layers followed by max-pooling layers and fully connected layers for classification.

## Convolutional Neural Networks (CNNs)
CNNs are a class of deep learning algorithms particularly effective for image recognition tasks. The main components of a CNN are:

- **Convolutional Layers:** These layers apply a set of filters to the input image, creating feature maps that detect various features like edges, textures, and shapes.
-**Activation Functions:** Typically, ReLU (Rectified Linear Unit) is used to introduce non-linearity into the model, allowing it to learn more complex patterns.
-**Pooling Layers:** These layers reduce the spatial dimensions of the feature maps, typically using max-pooling, which helps in reducing the computational load and controlling overfitting.
-**Fully Connected Layers:** These layers are used at the end of the network to perform classification based on the features extracted by the convolutional and pooling layers.

## Image Data Generation
To augment the dataset and improve the model's performance, image data generation techniques are used. This includes:

- **Rotation:** Rotating images at various angles.
- **Zoom:** Applying random zooms to images.
- **Flipping:** Horizontally or vertically flipping images.
- **Brightness Adjustment:** Randomly changing the brightness of images.
- **Shift:** Shifting images horizontally or vertically.

## Exploratory Data Analysis (EDA)
EDA is a crucial step in understanding the dataset before training the model. This involves:

- **Visualizing Image Samples:** Displaying random samples from the dataset to understand the variability and quality of images.
- **Label Distribution:** Analyzing the distribution of different aircraft types in the dataset to ensure balanced training.
- **Image Dimensions:** Checking the dimensions of images to ensure consistency.

## Dataset Preparation
Preparing the dataset involves several steps:

- **Sorting Aircraft:** Organizing images by aircraft type and other relevant categories.
- **Adding Names:** Labeling images with the appropriate aircraft names.
- **Label Allotment:** Assigning numerical labels to different aircraft types for training the CNN.
These steps ensure that the dataset is well-structured and ready for the training process.

## Real-World Applications
The Aircraft Recognition System using CNN has several real-world applications, including:

- **Surveillance:** Automatically detecting and identifying aircraft in satellite images for monitoring and security purposes.
- **Military Operations:** Enhancing reconnaissance capabilities by identifying aircraft in satellite imagery, aiding in strategic planning and threat assessment.
- **Air Traffic Management:** Assisting in the monitoring of air traffic by providing real-time data on aircraft positions and types.
- **Environmental Studies:** Analyzing air traffic patterns to study their impact on the environment and urban areas.
