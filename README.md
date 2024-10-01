
# BrainTumorPredictor

The focus of this project is on Brain Tumor MRI Classification using Convolutional Neural Network (CNN). It uses the Brain Tumor MRI Dataset from [Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).

## Roadmap

- Prerequisites

- Overview

- Author

## Prerequisites

- Jupyter
- Python 3
- PyTorch
- CUDA
- NumPy
- Matplotlib


## Overview

The dataset was downloaded from Kaggle and transformed for processing.  To keep things simple, I used just one channel instead of three because it didn’t really impact performance in my experiment. I built a CNN model with max pooling layers to help reduce the size of the data while keeping important features. Since this is a classification problem, added a classifier layer at the end.

The model was trained on the processed dataset, and its performance was visualized and evaluated. The results indicated that this architecture achieved good accuracy in classifying Brain Tumor Magnetic Resonance Imaging.



## Author

- [Agni Ramadani](https://github.com/agniramadani)
