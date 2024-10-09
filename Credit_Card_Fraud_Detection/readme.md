# Credit Card Fraud Detection

## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Significance](#significance)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Results](#results)
- [Conclusion](#conclusion)

## Project Overview
This project aims to develop a robust machine learning model for detecting credit card fraud. We utilize various techniques, including data preprocessing, feature selection, and model optimization, to enhance the model's performance and reliability in identifying fraudulent transactions.

## Objective
- **Binary Classification**: Develop a machine learning model to accurately classify credit card transactions as either genuine or fraudulent.
- **Handle Imbalance**: Implement techniques to address the class imbalance in the dataset, ensuring that the model can effectively detect fraudulent transactions even when they are rare.

## Significance
- **Financial Loss**: Accurate fraud detection can significantly reduce financial losses for both individuals and businesses.
- **Customer Protection**: By preventing fraudulent transactions, we can protect consumers from unauthorized charges and identity theft.
- **Industry Innovation**: The development of effective fraud detection models can drive innovation in the financial technology sector and contribute to the overall security of online transactions.

## Dataset
The dataset used for this project is the **Credit Card Fraud Detection Dataset**, which is available on Kaggle. Unfortunately, due to memory limitations, the entire dataset cannot be uploaded here. You can download it from the following link:  
[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data)

## Installation
To run this project, you will need the following libraries:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage
- Clone this repository to your local machine.
- Download the dataset from Kaggle and place it in the project directory.
- Run the Jupyter Notebook (fraud_detection.ipynb) in Google Colab or your local Jupyter environment.

## Data Preprocessing
The preprocessing steps include:

- Data loading and exploration.
- Handling missing values.
- Feature selection using techniques like SelectKBest.
- Addressing class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

## Model Training
We trained a Logistic Regression model with hyperparameter tuning using GridSearchCV to optimize performance. The model was evaluated using various metrics, including precision, recall, and F1-score.

## Results
              precision    recall  f1-score   support

           0       0.95      0.94      0.95     70804
           1       0.90      0.92      0.91     42497

    accuracy                           0.93    113301
   macro avg       0.93      0.93      0.93    113301
weighted avg       0.93      0.93      0.93    113301


## Conclusion
The Logistic Regression model, enhanced through data preprocessing techniques and hyperparameter optimization, provides a strong foundation for effective credit card fraud detection. Future work may focus on further improving the model’s performance by exploring advanced algorithms and feature engineering techniques.

