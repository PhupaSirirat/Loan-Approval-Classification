# Loan-Approval-Classification
## Overview
This project aims to classify loan approval status based on various features of the applicants. The dataset contains information such as applicant's income, loan amount, credit history, and more.

## Dataset
The dataset used in this project is named as `loan_data.csv`. 
This dataset is a synthetic version inspired by the original Credit Risk dataset on Kaggle and enriched with additional variables based on Financial Risk for Loan Approval data. SMOTENC was used to simulate new data points to enlarge the instances. The dataset is structured for both categorical and continuous features.

Data Aviable at: https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data


## Installation
To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install the required libraries using the following command:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Results (Random Forest Model)
```Classification Report:
               precision    recall  f1-score   support

           0       0.94      0.97      0.95      6990
           1       0.89      0.77      0.83      2010

    accuracy                           0.93      9000
   macro avg       0.91      0.87      0.89      9000
weighted avg       0.93      0.93      0.93      9000
```

## Confusion Matrix 
![image](https://github.com/user-attachments/assets/e707ab8a-eb3c-4463-ba6b-8f86a5f17108)


