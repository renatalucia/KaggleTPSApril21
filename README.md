# KaggleTPSApril21

## Introduction

This is project from the Kaggle Tabular Playground Series - Apr 2021.

The level of the competitions from the Tabular Playground Series are something in between a Getting Started and a Featured competition.

The dataset is used for the Apr 2021 competition is synthetic but based on a real dataset (the Titanic data) and generated using a CTGAN. The statistical properties of this dataset are very similar to the original Titanic dataset, but there's no way to "cheat" by using public labels for predictions.


## Project Structure

This project was structured with the following steps:

1. Data Collection
    * Consisted of downloading data from a Kaggle Dataset (tabular-playground-series-apr-2021)
2. Exploratory Data Analysis
    * Visualize Missing Values
    * Visualize feature distributions for train and test datasets
    * Visualize distribution of target value (Survived)
    * Visualize how diferent features are related to the target value (Survival rates according to parameters)
    * Select best features for the classification problem
3. Data Preparation
    * Encode categorial features
    * Create input and label vectors
    * Impute null values
    * Split data into train and validation
4. Classification Model
    * Define model
    * Compile model
    * Train model
    * Evaluate model on validation dataset
5. Preditions on Test Data
    * Predict target values for test data
    * Save file to submit on Kaggle

## Results
  The classification results were successfully submited on Kaggle with a private score of 0.78429
and a public score of 0.78755

