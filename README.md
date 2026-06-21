# Semantic Image Segmentation using U-Net

## Overview

This project develops a semantic image segmentation pipeline based on the U-Net architecture to identify and segment supermarket products in real-world images.

The objective is to assign a class label to every pixel in an image, enabling precise object localization and classification. The project explores both a baseline implementation and a series of improvements aimed at enhancing segmentation performance.

## Problem Description

Semantic segmentation is a computer vision task where each pixel of an image is assigned to a specific class.

In this project, the dataset consists of supermarket product images and their corresponding segmentation masks. The goal is to train a deep learning model capable of accurately identifying product categories and generating pixel-level predictions.

## Objectives

The project was divided into two main stages:

### Phase 1 – Baseline Segmentation Pipeline (Phase1.ipynb)

Development of an initial image segmentation pipeline using a compact U-Net architecture.

Main tasks:

* Dataset preparation and preprocessing.
* U-Net implementation.
* Model training and validation.
* Performance evaluation using segmentation metrics.

### Phase 2 – Model Improvements (Phase2.ipynb)

Several enhancements were explored to improve segmentation performance.

Potential improvements included:

* Data augmentation techniques.
* Alternative loss functions.
* Optimizer and learning rate tuning.
* Architectural modifications.
* Regularization techniques.
* Training strategy improvements.

The impact of each modification was evaluated and compared against the baseline model.

## Technologies Used

* Python
* PyTorch
* NumPy
* OpenCV
* Matplotlib
* TensorBoard

## Key Skills Demonstrated

* Deep Learning
* Computer Vision
* Semantic Segmentation
* Convolutional Neural Networks (CNNs)
* U-Net Architecture
* Hyperparameter Optimization
* Model Evaluation
* Data Preprocessing

## Results

The project successfully developed a semantic segmentation pipeline capable of generating pixel-level predictions for supermarket product images.

Different optimization and model improvement strategies were evaluated, providing insights into their impact on segmentation accuracy and model performance.

## Conclusion

This project demonstrates the application of deep learning techniques to a real-world computer vision problem. Through the implementation and improvement of a U-Net architecture, it highlights the importance of model design, preprocessing and training strategies in semantic image segmentation tasks.
