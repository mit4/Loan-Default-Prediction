# Loan Default Prediction

# Overview

With the improving banking sector in recent times and the increasing trend of taking loans, a large population applies for bank loans.
But one of the major problem banking sectors face in this ever-changing economy is the increasing rate of loan defaults.
The banking authorities are finding it more difficult to correctly assess loan requests and tackle the risks of people defaulting on loans.
The two most critical questions in the banking industry are
 * How risky is the borrower?, and
* Given the borrower’s risk, should we lend him/her?

## Problem:

Financial institutions incur significant losses due to the default of vehicle loans.
It has led to the tightening up of vehicle loan underwriting and increased vehicle loan rejection rates.
These institutions need and raise a requirement for a better credit risk assessment model.
It warrants a study to estimate the determinants of vehicle loan default.

## Goal
To accurately predict the probability of loanee/borrower defaulting on a vehicle loan in the first EMI (Equated Monthly Instalments).
Doing so will ensure that clients capable of repayment are not rejected and important determinants can be identified.This process can be further used for minimising the default rates.

# Data
Following Information regarding the loan and loanee are provided in the datasets:
* Loanee Information (Demographic data like age, Identity proof etc.)
* Loan Information (Disbursal details, loan to value ratio etc.)
* Bureau data & history (Bureau score, number of active accounts, the status of other loans, credit history etc.)

The dataset for loan default prediction is provided by L&T along with the respective data description as shown below.

| Records | Features | Size |
| :--: | :--: | :--: |
| 233154 | 41 | 39.8 MB|


# Conclusion

- We **analyzed** and understood the **behavior** of the data and performed manipulations accordingly.

- We **performed several transformations** over the l&t loan data as per the requirement.

- We **tried** out Logistic Regression, Random Forest, and XGBoost algorithm both by **baseline** and **oversampling**.

- It turns out that the **oversampled Random Forest** and **XGBoost model** gave us **good results**.

- We can choose either one, but we should always select a **generalized model** with **better scores**.
