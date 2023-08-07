# Loan Default Prediction


## Introduction

Welcome to the Loan Prediction Project! In this project, we analyzed and understood the behavior of the L&T loan dataset and performed various data manipulations to ensure the data is suitable for building predictive models. Our primary objective was to predict whether a loan applicant is likely to be approved or not based on various features available in the dataset.

## Goal
To accurately predict the probability of loanee/borrower defaulting on a vehicle loan in the first EMI (Equated Monthly Instalments).
Doing so will ensure that clients capable of repayment are not rejected and important determinants can be identified.This process can be further used for minimising the default rates.

## Data
Following Information regarding the loan and loanee are provided in the datasets:
* Loanee Information (Demographic data like age, Identity proof etc.)
* Loan Information (Disbursal details, loan to value ratio etc.)
* Bureau data & history (Bureau score, number of active accounts, the status of other loans, credit history etc.)

The dataset for loan default prediction is provided by L&T along with the respective data description as shown below.

| Records | Features | Size |
| :--: | :--: | :--: |
| 233154 | 41 | 39.8 MB|

 It is essential to note that the dataset might contain missing values, outliers, and class imbalance, which could impact the performance of our predictive models.


## Data Preprocessing

Before building predictive models, we performed several data preprocessing steps to clean and prepare the data for analysis. These steps included handling missing values, removing outliers, encoding categorical variables, and standardizing numerical features.

## Handling Imbalanced Data

Class imbalance is a common issue in loan prediction problems, where the number of approved loans (positive class) might be significantly lower than the number of rejected loans (negative class). To address this issue, we employed the Synthetic Minority Over-sampling Technique **(SMOTE)** to balance the dataset. SMOTE creates synthetic instances of the minority class to increase its representation in the dataset.


## Model Building

We trained several machine learning models on the preprocessed dataset to predict loan approval outcomes. The models we experimented with include:

1. Logistic Regression
2. Random Forest
3. XGBoost

## Model Evaluation

To assess the performance of our models, we used appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. We evaluated the models both on the original imbalanced dataset and the balanced dataset obtained after applying SMOTE.

## Results

After comparing the model performance, we found that the oversampled Random Forest and XGBoost models yielded the best results in terms of overall accuracy and other evaluation metrics. These models outperformed the baseline models, which were trained on the original imbalanced dataset.

## Conclusion

In conclusion, this loan prediction project involved data analysis, preprocessing, and model building to predict loan approval outcomes. By leveraging SMOTE to balance the imbalanced dataset, we improved the performance of our models significantly. The oversampled Random Forest and XGBoost models demonstrated excellent predictive capabilities, making them suitable choices for this task.

Feel free to explore the code in the provided Jupyter Notebook and refer to the documentation for more detailed insights into the project.
