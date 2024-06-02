# Advanced CNN for Pneumonia Detection in Chest X-Rays

## Overview
This project develops an advanced convolutional neural network (CNN) model to distinguish between normal and pneumonia-affected chest X-ray images.

## Prerequisites
- **Python Version**: 3.10
- **Required Libraries**: TensorFlow 2.10, Keras, NumPy, Matplotlib
  ```bash
  pip install tensorflow==2.10 keras numpy matplotlib
  ```

## Datasets
The model uses two key datasets from Kaggle:
1. [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) - Contains X-ray images categorized into normal and pneumonia.
2. [NIH Chest X-rays](https://www.kaggle.com/datasets/nih-chest-xrays/data) - A larger set of chest X-rays used to enhance the model's training.

## Model Architecture
The notebook details the setup of a deep convolutional neural network for binary classification, trained with techniques such as real-time data augmentation and batch processing to optimize performance.

## Usage
1. **Data Preparation**: Download and structure the images into directories by diagnosis and use case according to the paths specified in the notebook.
2. **Training**: Run the notebook cells to train the CNN. The training process involves extensive data augmentation to prevent overfitting.
3. **Evaluation**: After training, evaluate the model on a reserved test set to verify its generalization capability.

## Output
The trained model predicts whether chest X-rays show signs of pneumonia. Performance metrics such as accuracy and loss are plotted to assess the model's effectiveness.

