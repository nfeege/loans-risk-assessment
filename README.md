# Risk Assessment for Lending Club Loans

**Objective:** Predict whether a requested loan will be paid back in full or not (i.e. will be charged off) to help investors choose where to invest.

Risk assessment for loans using historic data from Lending Club and different machine learning algorithms. The main notebook of this project is ```loans-risk-assessment.ipynb```.

Background information on Lending Club:
https://www.lendingclub.com/public/how-peer-lending-works.action

## Installation and getting the data

1. Clone the repository from GitHub
 ```git clone https://github.com/nfeege/loans-risk-assessment```
2. Change into repository directory
 ```cd loans-risk-assessment```
3. Make the data directory
 ```mkdir data```
4. Data source (data on loans from Lending Club): https://www.lendingclub.com/info/download-data.action This notebook uses Lending Club Loan Data from 2007-2011 downloaded and saved as
 ```data/LoanStats3a_2007_2011.csv```
5. Use ```jupyter notebook``` to run the main notebook ```loans-risk-assessment.ipynb```

## Data description

Data source (data on loans from Lending Club):
https://www.lendingclub.com/info/download-data.action
LoanStats3a_2007_2011.csv = Lending Club Loan Data from 2007-2011

## Analysis

The Jupyter notebook for this analysis is ```loans-risk-assessment.ipynb```.

## Conclusion
The prediciton whether a loan will be paid back in full or not would inform the decision about whther to invest in the proposal or not. Here, we choose to minimize the risk for investing, i.e. we aim to minimize investing in proposals for which the loan will not be paid back. The Logistic Regression (with manual penalties) achieves 25% true positive rate at 9% false positive rate. This is the lowest false positive rate for all compared algorithms, so based on this study, this is the best choice when aiming to minimize loss of money to loans that are not being paid back in full.