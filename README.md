# Titanic-ML-From-Disaster 

This repository contains a machine learning project aimed at predicting the survival of passengers om the titanic using the famous Titanic Dataset. This project involves data preprocessing, exploratory data analysis, feature engineering, model training and evaluation. 

Project Overview

The goal of this project is to build a predictive model that answers the question "What sorts of people were likely to survive?" using passenger data (such as name, age, gender, socio-economic class etc). 

Dataset:

The dataset used in this project is provided by Kaggle and consists of two CSV files:

train.csv: The training dataset used to build the model.
test.csv: The test dataset used to evaluate the model.

Project Structure

Titanic-ML From Disaster.ipynb: The Jupyter notebook containing the entire project workflow.
train.csv: The training dataset.
test.csv: The test dataset.

Project Workflow

Data Loading: Load the training and test datasets.
Data Preprocessing:
Handling missing values.
Encoding categorical features.
Feature scaling.
Exploratory Data Analysis (EDA):
Visualizing the data.
Analyzing correlations between features and the target variable (Survival).
Feature Engineering:
Creating new features from existing ones.
Selecting relevant features for the model.

Model Training:

Splitting the data into training and validation sets.
Training various machine learning models (e.g., Logistic Regression, Decision Tree, Random Forest, etc.).
Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.

Model Evaluation:

Evaluating the model on the test dataset.
Analyzing the results and fine-tuning the model.

Results:
The final model achieves a confusion matrix on the test dataset. The results indicate that certain factors such as gender, age, and passenger class significantly influence the survival chances.

Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or additions.
