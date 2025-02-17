
KiTS23 Kidney and Kidney Tumor Segmentation Challenge 

**Overview**

Welcome to the repository for the 2023 Kidney and Kidney Tumor Segmentation Challenge (KiTS23). This challenge aims to develop the best system for automatic semantic segmentation of kidneys, renal tumors, and renal cysts using deep learning techniques.

**Project Objectives**

The primary objectives of this project are as follows:
Identify kidney tumors in CT scans with an accuracy higher than the industry standard of 83%, preferably achieving around 75%-80%.
Optionally, identify kidney structures and cysts if time permits.

**Methodologies**

We will approach the objectives using the following methodologies:
Implement a deep learning model based on a Convolutional Neural Network (CNN).
Experiment with different numbers of layers in the model, specifically using 8 layers.
Explore both object detection and instance segmentation techniques.
Consider using the UNet or ResNet architectures for the CNN model.

**Datasets**

We will utilize the provided dataset from the KiTS23 challenge, which includes:
An expanded training set consisting of 489 cases.
A new test set comprising 110 cases, including cases in the nephrogenic contrast phase.
CT scans showing kidney tumors, along with anonymized clinical information for each case.

**Preprocessing**

Preprocessing steps will include:
Ensuring all images are of the same size for consistency.
Filtering the dataset to include only images with more than one pixel value present.
Potential processing to handle pixel intensity ranges for tumor identification.

**Model Architecture**

The UNet architecture is favored for its suitability in medical image segmentation tasks:
Combines global and local features for high accuracy in segmentation.
Accepts various input data types, such as grayscale, color, and multi-channel images.
Originally designed for semantic segmentation of medical images.

**Getting Started**

Clone the repository to your local machine.
Install the required dependencies listed in requirements.txt.
Explore the dataset provided in the data directory.
Run the preprocessing scripts to prepare the data for training.
Train and evaluate the CNN model using the provided scripts.
