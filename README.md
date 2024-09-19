
# MRI Image Classification Project (Brain Tumor Detection) 🧠

## Overview

This project implements a Convolutional Neural Network (CNN) for classifying MRI images of brain tumors into four categories: glioma, meningioma, pituitary tumor, and no tumor. The goal is to provide a reliable automated method for assisting in medical diagnostics.

![Project Image](https://raw.githubusercontent.com/MJParviz/Brain_Tumor_Classification/main/Sample%20Mri%20Scan.png)

## Table of Contents 📚
- Project Description
- Requirements
- Dataset
- Model Architecture
- Training Process
- Results
- Challenges Encountered
- Conclusion

## Project Description
This project involves the following key steps:
- Data preprocessing and augmentation to enhance model generalization.
- Building a CNN model to classify images.
- Training and evaluating the model on a test dataset.
## Requirements ⚙️
To run this project, ensure you have the following libraries installed:- Python 3.x - TensorFlow - Keras- NumPy - Matplotlib - scikit-learn - seaborn
You can install the required libraries using pip:

`pip install tensorflow keras numpy matplotlib scikit-learn seaborn`

## Dataset 🖼️
The dataset consists of MRI images categorized into four classes:
- No Tumor 🚫
- Glioma 🧬
- Meningioma 🧠
- Pituitary Tumor 🎗️
Images are preprocessed by resizing to 512x512 pixels and normalized.

## Model Architecture 🏗️
The CNN model includes:
- **Input Layer**: Convolutional layers with ReLU activation.
- **Pooling Layers**: Max pooling layers to reduce dimensionality.
- **Fully Connected Layers**: Dense layers for classification with softmax activation._
*Model summary and architecture visualization are included in the code.*

## Training Process 🚀
-  **Data Augmentation**: Applied to the training set to improve generalization.
-  **Early Stopping**: Implemented to prevent overfitting.
-  **Loss Function**: Categorical cross-entropy used for multi-class classification.

## Results 📊
The model achieved satisfactory accuracy on the test set, with detailed metrics provided in the classification report. A confusion matrix illustrates performance across different classes.

## Challenges Encountered ⚠️
-  **Imbalanced Data**: Addressed using under-sampling techniques.
- **Overfitting**: Mitigated through data augmentation and early stopping.

## Conclusion 🎉
This project successfully demonstrates the implementation of a CNN for medical image classification. The techniques used, such as data augmentation and model evaluation, can be applied to various image-based tasks in healthcare and beyond. Future improvements could involve experimenting with different architectures or utilizing additional data.
