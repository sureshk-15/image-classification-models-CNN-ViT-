# image-classification-models-CNN-ViT-


# CNN vs ViT on Lumpy Skin Disease
This repository contains the code and experimental results for comparing Convolutional Neural Networks (CNN) with Vision Transformers (ViT) on the task of detecting Lumpy Skin Disease. The comparison includes three popular CNN models: DenseNet, InceptionV3, and VGG16.

# Dataset
The dataset used in this project consists of images of skin samples affected by Lumpy Skin Disease and Normal Skin.

# Preprocessing
Before training the models, several preprocessing steps were performed on the dataset:
K-means clustering: The images were clustered using the K-means algorithm to reduce the color space.
Discrete Wavelet Transform (DWT): The DWT was applied to decompose the images into different frequency bands.
Contour tracing: The contours of the skin lesions were extracted from the images.
The code for the preprocessing steps can be found in the preprocessing.ipynb notebook.

# Models
Three CNN models were used in this project: DenseNet, InceptionV3, and VGG16. The implementation of these models can be found in the DN_IV3_VGG16.ipynb notebook.

# Vision Transformer (ViT)
In addition to the CNN models, a Vision Transformer (ViT) was also trained and evaluated on the Lumpy Skin Disease dataset. The implementation of the ViT model can be found in the vit.ipynb notebook.
