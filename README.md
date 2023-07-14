# Digit Recognition using Convolutional Neural Network (CNN)

This repository contains code for training a CNN model to recognize handwritten digits from the MNIST dataset. The code utilizes the Keras library and implements data preprocessing, model training, and evaluation.

## Dataset

The code uses the MNIST dataset, which consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9). The dataset is divided into training and testing sets, and the model is trained on the training set and evaluated on the testing set.

## Steps

- Download the MNIST datasets train.csv, test.csv and sample_submission.csv from the link: https://www.kaggle.com/competitions/digit-recognizer/data and place the files in the project's root directory
- Run the Jupyter notebook digit-recognizer.ipynb in a Python environment with Jupyter Notebook installed.
- Follow the instructions in the notebook to execute each cell and run the code step-by-step.
- Use the model to make predictions on new images by loading the model and calling the appropriate methods.

  
## Results
The trained CNN model achieves an accuracy of approximately 99% on the test set. The model's performance can be visualized using the provided plots that show the training and validation accuracy and loss over epochs.
 
