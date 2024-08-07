# Breast-Cancer-Image-Segmentation-with-tensorflow-and-keras-U-net


## Description
This repository contains a project for breast cancer image segmentation using a U-Net model implemented with TensorFlow and Keras. The goal of the project is to develop a segmentation model that can identify and segment areas of interest in breast cancer images, which is crucial for the diagnosis and treatment of this disease. All development was done on Ubuntu 22.04.


## Requirements
Python 3.8 or higher


TensorFlow 2.x


Cuda drivers

## CUDA Drivers
To use GPU-accelerated training, you need to install CUDA drivers and cuDNN. Follow these steps to install them:

**Install NVIDIA Drivers**: Make sure you have the latest NVIDIA drivers installed. You can download the drivers from here: https://www.nvidia.com/Download/index.aspx


**Install CUDA Toolkit**: Download and install the CUDA Toolkit from the NVIDIA website: https://developer.nvidia.com/cudnn. 

Make sure to choose the version compatible with your TensorFlow version.


**Install cuDNN**: Download cuDNN from the NVIDIA website: https://developer.nvidia.com/cudnn. 

After downloading, unzip the files and copy the bin, include, and lib files to your corresponding CUDA directory.

## U-Net Model
The U-Net model is designed for image segmentation and consists of an encoder and a decoder with convolutional and transpose convolutional layers. The model is compiled using the 'adam' optimizer and the 'binary_crossentropy' loss function.

## Evaluation and Visualization
At the end of training, accuracy and loss plots are generated for both the training and validation sets.

