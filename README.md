# Kaggle Housing Prices Competition

This repository contains code that I developed for the 'Kaggle House Prices: Advanced Regression Techniques' competition.

## Competition Description

The goal of this competition is to predict the final price of each home in Ames, Iowa based on various features provided in the dataset. 

The evaluation metric for this competition is the Root Mean Squared Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.

For more details about the competition, you can visit the [competition page on Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

## Results

So far, the lowest RMSE I have been able to obtain using Gradient Boosting Regression has been 17970.28405.

## Repository Structure

- **data/ # Directory for storing dataset files.**

*train.csv # Training dataset.*

*test.csv # Testing dataset.*

- **notebooks/ # Jupyter notebooks for data analysis and model development.**

*main.ipynb # Notebook that contains all the code.*

- **models/ # Directory for storing trained models.**

*model.pkl # Trained model file.*

- **submissions/ # Directory for storing Kaggle smubmission files.**

*submission_gb.csv # Submission file for Kaggle.*

- **README.md # Readme file providing information about the repository.**
