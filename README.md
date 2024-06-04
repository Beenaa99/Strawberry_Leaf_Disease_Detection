# Strawberry Leaf Disease Detection

## Overview

This project focuses on the detection and classification of various diseases in strawberry leaves using machine learning techniques. The project starts with Exploratory Data Analysis (EDA) and aims to develop a multi-label classification model to identify whether a leaf is healthy or infected, and if infected, the type of infection. The targeted diseases are angular leaf spots, leaf scorch, and leaf spot. It is part of the Omdena Project - Agritech Milan. 

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [EDA](#eda)
- [Data Augmentation](#data-augmentation)
- [Model Training](#model-training)
- [Results](#results)

## Introduction

The goal of this project is to accurately classify strawberry leaf diseases using image data. The diseases targeted include angular leaf spots, leaf scorch, and leaf spot, along with healthy leaves. This project involves data preparation, EDA, model training, and evaluation.

## Dataset

Comprises images of strawberry leaves categorized into four classes and are collected from open sourcen datasets:
- **Healthy leaves**
- **Angular leaf spots (bacteria)**
- **Leaf scorch (fungus)**
- **Leaf spot (fungus)**

The images are stored in respective folders, and the initial step involves renaming the image files for consistency and easier processing. The images are then loaded into the notebook for further analysis.

## EDA

Exploratory Data Analysis (EDA) is conducted to understand the distribution and characteristics of the dataset. This involves:
- Visualizing sample images from each category.
- Analyzing the distribution of images across categories.
- Preprocessing images for model training.

The EDA process helps in identifying any imbalances in the dataset and understanding the diversity of the images.

## Data Augmentation

To address the imbalances in the dataset, data augmentation techniques are employed. This involves generating new images through transformations such as rotation, width and height shifts, shear, zoom, and horizontal flips. Data augmentation increases the number of images in underrepresented categories, helping to improve the robustness and generalization of the classification model.

## Model Training

The project aims to develop a multi-label classification model using deep learning techniques. The model training process includes:
- Defining the architecture of the neural network.
- Setting up the training parameters and hyperparameters.
- Training the model on the prepared and augmented dataset.
- Evaluating the model performance using appropriate metrics.

Details on the specific architecture, training procedures, and hyperparameters will be documented as the project progresses.

## Results

Quantitative and qualitative results of the model performance will be documented. This includes metrics such as accuracy, precision, recall, and F1-score, as well as visualizations of the model's predictions on sample images.




