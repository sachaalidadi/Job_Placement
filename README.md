## About this repository

This repository contains a machine learning model that predicts if a candidate will be hired or not.

The training of this model can be found in the python notebook named `model_training.ipynb`

## About the notebook

The notebook contains two parts:

* EDA (Exploratory Data Analysis): Where we perform a statistical analysis of our dataset
* Model training: We select the relevant models for our problem and optimize the hyperparameters of the model

## About the dataset

The dataset is a .csv file containing several informations about the candidate.

It was found on the site kaggle.com, you can find it [here](https://www.kaggle.com/code/prasadshingare/job-placement-dataset#Job-Placement-Dataset)

## How to replicate the results

The dataset can be found in the repository under the name `Job_Placement_Data.csv`

To execute the notebook, you need Python 3 and the following libraries:

* matplotlib
* numpy
* pandas
* seaborn
* sklearn

You can install these libraries using the following command:

```shell
pip install requirements.txt
```

requirements.txt is the txt file containing the names of the necessary libraries