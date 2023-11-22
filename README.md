# Financial Risk Assessment for Loan Default Prediction

This project is part of the Datawhale and Tianchi beginner series and is the fourth installment - "Introduction to Financial Risk Assessment: Loan Default Prediction" for individuals to practice Machine Learning.

## Project Overview

The goal of this project is to predict the likelihood of loan default for individual loan applicants in the context of financial risk assessment. Participants are required to use the data provided to make predictions based on the applicant's information and decide whether to approve or reject the loan application. This is a typical classification problem.

## Project Folder Structure

This project is organized with the following folder structure:

- [`dataset`](./dataset): Contains the raw dataset files.

  - [`testA.csv`](./dataset/testA.csv): The raw testing dataset.
  - [`train.csv`](./dataset/train.csv): The raw training dataset.

- [`model`](./model): Contains the trained machine learning model.

  - [`lgb_model.pkl`](./model/lgb_model.pkl): The trained Light Gradient Boosting (LGB) model.

- [`process_datas`](./process_datas): Contains preprocessed data and intermediate files.

  - [`test_process_datas.csv`](./process_datas/test_process_datas.csv): The preprocessed testing dataset of features.
  - [`train_process_datas_x.csv`](./process_datas/train_process_datas_x.csv): The preprocessed training dataset of features.
  - [`train_datas_Y.csv`](./process_datas/train_datas_Y.csv): The preprocessed training dataset of true values.

- [`predict`](./predict): Contains prediction-related files.

  - [`lgb_submit_proba.csv`](./predict/lgb_submit_proba.csv): The predicted probability for the testing dataset.
  - [`lgb_submit.csv`](./predict/lgb_submit.csv): The predicted labels for the testing dataset.

- [`data_analysis.ipynb`](./data_analysis.ipynb): Jupyter Notebook file for data preprocessing.
- [`lgb_train_main.ipynb`](./lgb_train_main.ipynb): Jupyter Notebook file for training the Light Gradient Boosting model.
- [`predict_main.ipynb`](./predict_main.ipynb): Jupyter Notebook file for predicting labels for the testing dataset.

## Getting Started

To get started with the project, follow these steps:

1. Clone this repository to your local machine.
2. Place the dataset files in the `dataset` folder.
3. Run the appropriate Jupyter Notebook files (`data_analysis.ipynb`, `lgb_train_main.ipynb`, `predict_main.ipynb`) to perform data preprocessing, model training, and predictions.
