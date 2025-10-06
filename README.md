# POTATO-DISEASE-CLASSIFICATION
This project focuses on building a Convolutional Neural Network (CNN) to classify potato leaf images into different categories of plant health and disease. The dataset used is a subset of the PlantVillage dataset, which contains labeled images of healthy and diseased potato plants.

The goal is to assist farmers and researchers in quickly identifying potato diseases to improve crop management and yield.

# Dataset
Source: PlantVillage Dataset

Classes:

Potato — Healthy
Potato — Early Blight
Potato — Late Blight

The dataset is organized in subfolders, each representing a class.

# Project Workflow
## Data Preparation
Load dataset using image_dataset_from_directory

Split into Train (80%), Validation (10%), and Test (10%)

Resize all images to 256×256 and normalize pixel values
