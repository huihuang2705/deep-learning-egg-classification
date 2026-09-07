# Deep Learning Image Classification

A binary image classification project implemented with TensorFlow/Keras.

The project compares a custom CNN baseline with transfer learning models including MobileNetV2, VGG16 and ResNet50.

## Overview

The goal of this project is to develop an image classification pipeline and evaluate different convolutional neural network architectures for a two-class classification problem.

The project includes:

- Image dataset preparation
- Image normalization
- Custom CNN baseline
- Transfer learning with ImageNet pretrained models
- Model fine-tuning
- Model evaluation
- Single-image inference

## Sample Images

<img width="1004" height="400" alt="image" src="https://github.com/user-attachments/assets/c2bfac00-42af-4c6e-91f8-ae7be20c5d4f" />


## Models

The following architectures are implemented:

### Custom CNN

A convolutional neural network built from scratch and used as the baseline model.

### MobileNetV2

A lightweight ImageNet-pretrained network used for transfer learning.

### VGG16

A pretrained CNN with the final layers fine-tuned for the target classification task.

### ResNet50

A residual neural network pretrained on ImageNet and adapted for binary classification.

## Prediction Example

<img width="941" height="511" alt="image" src="https://github.com/user-attachments/assets/c389d222-e34b-491d-b46f-0be0f58a71bd" />


## Technologies

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Pillow
- Matplotlib

## Project Structure

```text
deep-learning-image-classification/
│
├── Image_Classification.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
└── assets/
    ├── sample_images.png
    └── prediction_example.png
