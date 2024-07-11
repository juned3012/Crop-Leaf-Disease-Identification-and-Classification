# Crop Leaf Disease Identification and Classification

Welcome to the **Crop Leaf Disease Identification and Classification** project repository. This project focuses on identifying and classifying crop leaf diseases using deep learning models. The goal is to accurately classify diseases in crop leaves based on images from the Plant Village dataset.

## Table of Contents
- [Crop Leaf Disease Identification and Classification](#crop-leaf-disease-identification-and-classification)
  - [Table of Contents](#table-of-contents)
  - [Models Implemented](#models-implemented)
  - [Contents](#contents)
    - [Notebook Files](#notebook-files)
    - [Trained Models](#trained-models)
    - [Dataset](#dataset)
    - [Prediction on Unseen Data](#prediction-on-unseen-data)

## Models Implemented

The following deep learning models have been implemented and evaluated for crop leaf disease classification:

- VGG16
- VGG19
- MobileNet
- ResNet50
- InceptionV3

Each model is trained using the Plant Village dataset, which includes images from multiple classes of crop diseases.

## Contents

### Notebook Files

Jupyter notebooks are provided for each model implementation and evaluation. These notebooks detail the process of training, evaluating, and fine-tuning each model using the Plant Village dataset.

### Trained Models

Pre-trained model files (*.h5) are available for VGG16 and InceptionV3. These models can be used for disease classification tasks on new images after training.

### Dataset

Sample images from the Plant Village dataset are included in the repository for demonstration purposes. The full dataset can be accessed from the Plant Village website for extensive training and testing.

### Prediction on Unseen Data

The `prediction_on_unseen_data.ipynb` notebook demonstrates how the trained models can be used to predict disease classes on unseen images. This showcases the practical application of the models for real-world disease identification scenarios.

Feel free to explore the notebooks and trained models to understand how each model was implemented and evaluated. The `prediction_on_unseen_data.ipynb` notebook provides insights into deploying these models for disease classification tasks on new crop leaf images.

