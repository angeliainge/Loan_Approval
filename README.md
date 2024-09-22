The housing market, essential for economic stability, is currently at risk due to soaring prices and rising mortgage delinquencies in Canada. Drawing lessons from the 2008 housing crisis, this paper explores the role of risk management and technological innovation in loan approval processes. Given the increasing complexity of home loans, we propose a machine learning model to enhance the accuracy and efficiency of home loan assessments.

This Python project starts with dataset exploration, followed by data cleaning, transformation, and visualization. We then implement five machine learning models to evaluate their accuracies and identify the best-performing algorithm for optimal business solutions.

Dataset-Overview

The dataset, collected by Konapure [https://www.kaggle.com/datasets/rishikeshkonapure/home-loan-approval] for Dream Housing Finance company, consists of a train and test set, each with 13 columns. The columns and encoded values are as follow:

1. Loan_ID
2. Gender - Female: 0; Male: 1
3. Married – No: 0; Yes: 1
4. Dependents – 0: 0 ; 1: 1; 2: 2; 3+:3
5. Education – Graduate: 0; Not Graduate: 1
6. Self_Employed – No: 0; Yes: 1
7. ApplicantIncome
8. CoapplicantIncome
9. LoanAmount
10. Loan_Amount_Term
11. Credit_History: No: 0; Yes: 1
12. Property_Area: Rural: 0; Semiurban: 1; Urban: 2
13. Loan_Status (only train set)
