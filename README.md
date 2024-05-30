# Pneumonia Detection with Convolutional Neural Networks

## Overview

This project aims to leverage image detection technology, specifically Convolutional Neural Networks (CNNs), to develop a model capable of accurately predicting whether a patient has pneumonia or not based on X-ray images. This is a process that is very difficult even for a doctor that has years of experience and highlights the vast impacts that image-detection can have in the healthcare sector. The process involves importing X-ray images from Google Drive, preprocessing steps such as image resizing and data augmentation, splitting the dataset into training, validation, and test sets, and implementing a classification model for pneumonia detection.

## Dataset

The X-ray images used for this project are sourced from Google Drive. These images consist of chest X-rays labeled with pneumonia-positive and pneumonia-negative cases. The dataset will be preprocessed and split into training, validation, and test sets to train and evaluate the CNN model.

## Data
You will be able to download and locate the data from the following link:https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

In order to follow the same format as given in the code you can upload to google drive as per the code provided and allow Google Colab to mount to the drive to extract the information.

## Methodology

1. **Data Import:** X-ray images will be imported from Google Drive into the project environment.
2. **Data Preprocessing:** Image resizing and data augmentation techniques will be applied to prepare the dataset for training.
3. **Dataset Splitting:** The dataset will be divided into training, validation, and test sets to train, validate, and evaluate the CNN model.
4. **Model Development:** A CNN model will be constructed to learn features from the X-ray images and classify them into pneumonia-positive or pneumonia-negative classes.
5. **Model Evaluation:** The trained model will be evaluated using the test set to assess its performance in pneumonia detection.

## Contributors

- [Shaun Commee](shauncommee@hotmail.co.uk)

## License

This project is licensed under the [MIT License](LICENSE)
