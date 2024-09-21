# Logistic Regression Classification

This project implements Logistic Regression for a binary classification task using a dataset related to advertising.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data Exploration](#data-exploration)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)

## Introduction
This project aims to classify whether a user clicked on an advertisement based on various features. Logistic Regression serves as the primary algorithm for this classification task.

## Installation
To run this project, install the following packages:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## Usage
1. Clone the repository.
2. Navigate to the project directory.
3. Open the Jupyter Notebook and run the cells to perform data analysis, training, and evaluation.

## Data Exploration
The dataset `advertising.csv` includes features such as:
- Age
- Gender
- Estimated Salary
- Purchased (target variable)

## Visualizations
The notebook includes several visualizations to analyze the data:
- Age Distribution
- Income vs Age
- Daily Internet Usage by Gender:


Explore the dataset using Pandas and visualize it with Matplotlib and Seaborn.

## Model Training and Evaluation
Logistic Regression is used to classify whether a user will click on an ad. The notebook includes:
- Feature selection
- Data splitting
- Model training
- Predictions and evaluations

## Model Evaluation
Evaluate the model using accuracy, confusion matrix, and other relevant metrics.

## Hyperparameter Tuning
The notebook also performs hyperparameter tuning using GridSearchCV to optimize the model. After tuning the hyperparameters, the accuracy of the model improved.

## Conclusion
The Logistic Regression model was successfully trained and evaluated. Future work could involve experimenting with different models and hyperparameters.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
