# Lending Club Loan Repayment Prediction
---
This project explores publicly available data from LendingClub.com, which connects borrowers with investors. The goal is to create a model to predict whether a borrower will repay their loan in full.

## Project Overview

**Data Source:** LendingClub.com (2007-2010)  
**Objective:** Classify and predict loan repayment status  
**Techniques Used:** Decision Trees, Random Forests

## Data Description

- **credit.policy:** 1 if the customer meets LendingClub’s criteria, 0 otherwise
- **purpose:** Purpose of the loan (e.g., credit_card, debt_consolidation)
- **int.rate:** Interest rate of the loan
- **installment:** Monthly installments owed by the borrower
- **log.annual.inc:** Natural log of the borrower’s annual income
- **dti:** Debt-to-income ratio
- **fico:** FICO credit score
- **days.with.cr.line:** Number of days the borrower has had a credit line
- **revol.bal:** Revolving balance
- **revol.util:** Revolving line utilization rate
- **inq.last.6mths:** Number of inquiries in the last 6 months
- **delinq.2yrs:** Number of times the borrower was 30+ days past due in the last 2 years
- **pub.rec:** Number of derogatory public records

## Exploratory Data Analysis

- **Histograms:** FICO scores based on credit policy and repayment status
- **Countplot:** Loan purposes with repayment status
- **Jointplot:** FICO score vs. interest rate
- **Lmplots:** Trends between FICO score and interest rate based on credit policy and repayment status

## Model Training

- **Decision Tree:** Trained and evaluated using classification report and confusion matrix
- **Random Forest:** Trained with 200 estimators and evaluated similarly

## Conclusion

The Random Forest model performed better in terms of accuracy but requires more feature engineering for improved recall.

---

Feel free to explore the code and provide any feedback or suggestions!
