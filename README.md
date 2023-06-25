# Analysis of Emotional Intensity of Tweets

This repository contains notebooks and datasets for the analysis of emotional intensity in tweets. The project aims to accurately predict and quantify the intensity of emotions expressed in social media conversations using both statistical and deep learning models.

## Notebooks

- [Pycaret_preprocessing.ipynb](models/Pycaret_preprocessing.ipynb): This notebook contains the codes for preprocessing the text data and converting it ready to be loaded in a machine learning model. It uses Pycaret - a low code machine learning library to do the work.
  
- [Statistical_model.ipynb](models/Statistical_model.ipynb): This notebook focuses on the statistical analysis of emotional intensity in tweets. It includes data preprocessing, exploratory data analysis, and the implementation of various statistical models for emotion prediction.

- [Deep Learning_model.ipynb](models/Deep_learning_model.ipynb): This notebook explores the use of deep learning models for predicting emotional intensity in tweets. It includes data preprocessing, model development using deep learning architectures, hyperparameter tuning, and model evaluation.

## Datasets

- [train_emoln.txt](models/train_emoln.text): The train dataset.

- [test_emoln.txt](models/test_emoln.text): The test dataset.

## Requirements

- [requirements.txt](requirements.txt): The file listing the required Python packages and dependencies to run the notebooks.

## Usage

1. Download the datasets.
2.  Open the PyCaret_preprocessing.ipynb in Google Colab and upload the datasets.
3.  Update the names of the files as required.
4.  After preprocessing is done , you will get the data as two csv files - train and test.
5.  Upload the files in any of the notebooks and run the cells to execute the model.

   ## Note : Make sure you have installed the requirements.txt in the notebooks.

Feel free to contribute and improve this model by submitting issues or pull requests.
