# Credit Risk Prediction

## Overview
This repository contains the implementation of a machine learning model for predicting credit risk. The project is part of the Module Challenge, focusing on assessing loan risk using logistic regression.

## Objective
The goal is to build and evaluate a logistic regression model that can accurately predict whether a loan is high-risk or healthy based on various financial indicators.

## Dataset
The model is trained and tested on a dataset containing features like loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status.

## Methodology
1. **Data Preprocessing**: The dataset is split into training and testing sets, and features are selected for model training.
2. **Model Training**: A logistic regression model is trained first on the original dataset and then on the resampled dataset using `RandomOverSampler` to handle class imbalance.
3. **Model Evaluation**: The model's performance is evaluated using metrics like accuracy, precision, recall, F1-score, and the confusion matrix.

## Results
- The model shows high effectiveness in predicting both healthy and high-risk loans.
- Balanced accuracy score and classification report indicate the model's robustness, especially after resampling the training data.

## Usage
Instructions for setting up, running, and evaluating the model are provided in the Jupyter notebooks within this repository.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Project
Project Link: [https://github.com/data-analyst05/credit-risk-prediction](https://github.com/data-analyst05/credit-risk-prediction)
