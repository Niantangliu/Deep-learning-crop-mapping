# Deep Learning for Crop Mapping

Welcome to our repository, where we explore the cutting-edge deep learning architectures applied to crop mapping. This project aims to enhance crop classification accuracy by using the power of AI.

# Overview
This repository contains a series of experiments and implementations of various deep learning models designed to identify, classify, and map different crop types using satellite imagery. By integrating different architectures, we aim to compare their effectiveness and accuracy in real-world scenarios, contributing to optimising crop type predictions and land use efficiency.

# Models Explored

## RNN (Recurrent Neural Networks): 
Applied to temporal sequences, ideal for analyzing changes over time in crop growth.
## Transformer: 
Utilized for large-scale and high-resolution imagery, focusing on capturing complex, long-range dependencies.
## 1D-CNN (One-Dimensional Convolutional Neural Network): 
Optimized for analyzing sequential data, this model is ideal for extracting features from temporal profiles of crop growth captured in time-series satellite data.
## 3D-CNN (Three-Dimensional Convolutional Neural Network): 
Designed to interpret volumetric data, enabling the analysis of spatial-temporal patterns in multi-temporal imagery.
## AtLSTM (Attention-based Long Short-Term Memory): 
A type of recurrent neural network with an attention operation, capable of learning order dependence in sequence prediction problems, particularly useful for time-series prediction in crop development.
## ConvRNN (Convolutional Recurrent Neural Network): 
Combines CNNs and RNNs to interpret spatial and temporal data simultaneously, providing a robust framework for dynamic environmental understanding.
## Attention 3D U-net: 
An adaptation of the U-Net architecture that works with volumetric data, perfect for detailed segmentation tasks in 3D medical images and adapted here for high-resolution crop classification.
## Model ensemble learning and hybrid architectures
Ensemble learning jointly combines multiple models to improve accuracy, robustness, and generalisation beyond what single models achieve. Ensemble methods help reduce overfitting and enhance prediction capabilities on complex datasets. Hybrid architectures merge different types of neural networks or combine neural networks in order, such as using CNNs' outputs as inputs into RNNs.

# Model interpretation
To deepen our understanding of the models' decision-making processes and improve their transparency and usability, we explore model interpretation from three perspectives:

1. Unveiling Model Learning Behavior
We analyze how models evolve during training, focusing on understanding the changes in their internal state across convolutional layers and time series. 

2. Soft Output (Prediction Confidence)
We examine the confidence levels of the model predictions to assess their reliability. 

3. Gradients for visualising Important Features and Acquisition Dates
By analyzing the gradients, we explore which features (e.g., satellite-derived features, temporal windows) contribute most to the model's predictions.


# Dataset
The datasets used in this project are sourced from public satellite imagery (mainly Sentinel-1 and Sentinel-2) and agricultural surveys conducted by the Chinese Academy of Agriculture Science (CAAS). Due to the large data volume, the preprocessed data for model training and evaluation is not directly provided here. Still, we will keep uploading demo datasets and updating this repository accordingly.

# Tools and Technologies
  TensorFlow
  numpy
  pandas
  scikit-learn
  jupyter

# Getting Started
Clone this repo to begin exploring different neural networks' performance on crop mapping. Installation guidelines, usage instructions, and detailed documentation are provided for setting up your environment and running the models.

# Contribution
Contributions are welcome! If you have suggestions for new models, improvements in the existing ones, or additional datasets, please feel free to open an issue or submit a pull request.

# License
This project is released under the MIT License. Please refer to the LICENSE file for more details.
