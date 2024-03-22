# Face_Detection
Individual Project


#  Face Detection of Retinaface and Dlib 

This project demonstrates the implementation of face detection using two different methods: Retinaface, a deep learning-based approach using PyTorch, and Dlib, a popular library for computer vision tasks.

## Introduction

Face detection is a fundamental task in computer vision, with numerous applications ranging from security surveillance to facial recognition systems. This project explores two distinct approaches to face detection:

1. **Retinaface**: Utilizes a deep neural network architecture for accurate and efficient face detection. Retinaface is implemented using PyTorch and provides state-of-the-art performance in detecting faces under various conditions.

2. **Dlib**: Employs a classical approach to face detection using the Dlib library. Dlib offers a robust face detector based on a combination of HOG (Histogram of Oriented Gradients) features and a linear SVM (Support Vector Machine) classifier.

## Installation

You can install the required Python packages using pip:

!pip install torch==1.7.1+cu110 torchvision==0.8.2+cu110 -f https://download.pytorch.org/whl/torch_stable.html
!pip install opencv-python==4.8.0.76 matplotlib
!pip install python-time
!git clone https://github.com/sachadee/Dlib.git or python -m pip install dlib-19.22.99-cp38-cp38m-win_amd64.whl
!git clone https://github.com/biubug6/Pytorch_Retinaface.git

## Dataset

The dataset used in this project is the WIDER FACE dataset, which can be downloaded from [here](http://shuoyang1213.me/WIDERFACE/WiderFace_Results.html).

