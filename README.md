# Age and Gender Classification Using Convolutional Neural Networks

This repository contains the code and report for a deep learning project that performs gender classification and age estimation from facial images. The work compares two approaches:

1. A custom convolutional neural network built from scratch  
2. A VGG16 model adapted and trained using transfer learning

Both models were trained on a subset of 5000 from the UTKFace dataset.

## Report

The full report is included in this repository as a PDF. It describes the dataset, model architecture, data processing pipeline, training configuration, and results.

## Model files

Model A: Custom CNN  
Google Drive link  
[Link](https://drive.google.com/file/d/1Ov8IhEn_XFFpLteQ4srk8unwCviGJrUR/view?usp=sharing)

Model B: Fine tuned VGG16  
Google Drive link  
[Link](https://drive.google.com/file/d/1MiKz51OFIISj58-R-AD_452BhweScJI5/view?usp=sharing)

## Contents of the repository

* Jupyter notebook containing the training pipeline  
* PDF of the project report  
* Sample figures including training curves and dataset analysis  
* Links to the saved models in Google Drive

## Requirements

This project was developed and run on Google Colab and will require packages such as:

* TensorFlow
* Keras
* NumPy
* Matplotlib
* cv2
* ...

## How to run

1. Open the Jupyter notebook  
2. Ensure the dataset folder path is set correctly, with the correct image size.  
3. Run all cells to reproduce the training and evaluation results  
4. If you download the model files, place them in a models directory or update the paths in the notebook

## Notes on the dataset

This project uses a subset of the UTKFace dataset with rescaled images to the size 128x128x3 instead of 200x200x3. The full dataset is available for non commercial academic use.
