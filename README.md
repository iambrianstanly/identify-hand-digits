# Sign Language Digit Recognition using CNN
This project focuses on recognizing hand gesture digits (0-9) using a Convolutional Neural Network (CNN). The CNN model is trained on a dataset of hand gesture images, where each image corresponds to a specific digit. The primary goal is to develop a robust and accurate model that can be used in various applications, such as touchless user interfaces, sign language interpretation, and augmented reality systems.

# Pipeline
## Dataset Collection
The dataset was collected from Kaggle website [Sign language digit Dataset](https://www.kaggle.com/datasets/ardamavi/sign-language-digits-dataset/data)

## EDA
Analysing the dataset and come with some hypothesis.

## Data Preprocessing
Using tensorflow framework to preprocess the images (ie; resizing, normalising)

## Model Architecture
Design CNN model suitable for classficationt task.

## Model Training
Splitting data into training testing and choosing appropriate loss function and optimizer ('sparse categorical crossentropy', 'Adam')

## teesting and validation
Evaluated the trained model with unseen test data samples.

# Language and frameworks
- language: python
- framework: tensorflow
- image processing: opencv
