# POTATO-DISEASE-CLASSIFICATION
This project focuses on building a Convolutional Neural Network (CNN) to classify potato leaf images into different categories of plant health and disease. The dataset used is a subset of the PlantVillage dataset, which contains labeled images of healthy and diseased potato plants.

The goal is to assist farmers and researchers in quickly identifying potato diseases to improve crop management and yield.

# Dataset
Source: PlantVillage Dataset

### Classes:

Potato — Healthy

Potato — Early Blight

Potato — Late Blight

The dataset is organized in subfolders, each representing a class.

# Project Workflow
## Data Preparation
Load dataset using image_dataset_from_directory

Split into Train (80%), Validation (10%), and Test (10%)

Resize all images to 256×256 and normalize pixel values
## Model Architecture
Implemented with TensorFlow / Keras

### Typical CNN layers:

Convolutional layers with ReLU activation

MaxPooling layers

Dropout for regularization

Dense (Fully Connected) layers

Output layer with Softmax activation (3 classes)

## Training
Optimizer: Adam

Loss Function: SparseCategoricalCrossentropy

Epochs: 5 (can be increased for better accuracy)

Batch Size: 32

## Evaluation

Accuracy and Loss curves visualized with Matplotlib

Tested on unseen validation and test sets

## Prediction

Model predicts class of uploaded leaf image

Sample predictions are displayed with labels

# Results 
The model achieves promising accuracy on the test set after just 5 epochs.

With further tuning (increasing epochs, data augmentation, transfer learning), performance can be improved significantly.
