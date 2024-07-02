LINK FOR DATASET 
https://drive.google.com/drive/folders/12N2MgmFcQdM-NdWeL_hIwNJF_NjYH1MG?usp=share_link

Deepfake Image Detection 

Overview 

This repository contains the code and resources for detecting deepfake images using a Convolutional Neural Network (CNN) model. Our model achieves an accuracy between 88% to 94%, making it a robust tool for identifying manipulated images. 

Table of Contents 

Introduction 

Dataset 

Model Architecture 

Training 

Results 

Installation 

Acknowledgements 

Introduction 

Deepfake technology has advanced significantly, posing a threat by enabling the creation of realistic but fake images and videos. Our project aims to detect these deepfakes using a CNN model trained on a dataset of genuine and manipulated images. 

Dataset 

We used a comprehensive dataset comprising both real and deepfake images for training and validation. The dataset is split into training, validation, and testing sets. 

Training Set: https://drive.google.com/drive/folders/12N2MgmFcQdM-NdWeL_hIwNJF_NjYH1MG?usp=share_link 

Model Architecture 

Our model is based on a Convolutional Neural Network (CNN) architecture. The key layers and parameters are as follows: 

Input Layer: 224x224 RGB images 

Convolutional Layers: Multiple layers with ReLU activation 

Pooling Layers: Max pooling for downsampling 

Fully Connected Layers: Dense layers for classification 

Output Layer: Softmax layer for binary classification 

Training 

The model was trained using the following parameters: 

Optimizer: Adam 

Loss Function: Binary Cross-Entropy 

Batch Size: 32 

Epochs: 55 

Training was conducted on a GPU-enabled environment to speed up the process. 

Results 

Our CNN model achieved the following results: 

Training Accuracy: 92% 

Validation Accuracy: 90% 

Test Accuracy: Between 88% to 94% 

These results indicate the model's efficacy in distinguishing between real and deepfake images. 

Installation
To get started, clone this repository and install the required dependencies:

git clone https://github.com/yourusername/deepfake-detection.git
cd deepfake-detection
pip install -r requirements.txt

Acknowledgements
We would like to thank the following resources and communities:

TensorFlow
Kaggle for providing the dataset
The GitHub community for support and collaboration




