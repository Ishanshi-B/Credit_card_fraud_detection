# Credit Card Fraud Detection

This project aims to detect credit card fraud using machine learning techniques in Python. The goal is to identify fraudulent transactions from a dataset with an imbalanced distribution between legitimate and fraudulent transactions.

## Dataset

The dataset used in this project is sourced from Kaggle and can be accessed [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download). It contains transaction records including features derived from Principal Component Analysis (PCA) and transaction amounts.

## Project Outline

### Data Exploration

The initial step involves loading the dataset and examining its structure. Key aspects include understanding the features, which consist of transformed data (V1, V2, ..., V28) and transaction details such as `Amount`. The `Class` column indicates the nature of the transaction, where `0` represents a legitimate transaction and `1` represents a fraudulent one.

### Handling Imbalance

Given the imbalanced nature of the dataset, the project employs undersampling techniques to create a balanced dataset. This involves reducing the number of legitimate transactions to match the number of fraudulent transactions, ensuring a more effective training process.

### Data Preparation

The data is then split into features and target variables. The dataset is divided into training and testing sets to evaluate the model's performance. This separation allows the model to be trained on one subset and tested on another to assess its accuracy and generalization.

### Model Training and Evaluation

A logistic regression model is trained on the prepared dataset. The performance of the model is evaluated using accuracy scores, which provide insights into how well the model identifies fraudulent transactions compared to legitimate ones.

## Conclusion

This project showcases the application of machine learning techniques to credit card fraud detection. By preprocessing the data and utilizing logistic regression, the project aims to achieve effective classification of transactions, enhancing the ability to detect fraudulent activities.
