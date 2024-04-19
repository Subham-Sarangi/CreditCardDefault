# Credit Card Default Prediction Analysis 🛡️💳

## Introduction
Financial institutions increasingly rely on models and algorithms to forecast losses due to client defaults. For internal risk management and regulatory obligations, financial institutions must assess the risks in their credit portfolios. Therefore, one of the main initiatives of quantitative risk management groups inside these organizations is to build models that are sufficiently accurate and reliable.

## Problem Statement 🎯
A Taiwanese credit card company seeks to enhance its ability to predict customer default and identify the major factors influencing this risk. This study aims to discover the main factors that influence the chance of credit card default by utilizing certain supervised machine learning methods.

## Objective 📈
The objective is to pinpoint the crucial elements and forecast credit card defaults using client data and previous transactions. This information enables issuers to make informed decisions about who receives credit cards and what credit limits they'll be given. Additionally, it aids issuers or companies in better comprehending their present and potential clients, leading future strategies and plans for providing their clients with specialized financing solutions.

## Data Understanding 📊💡
The dataset contains billing statements, credit history, payment history, and default information for Taiwanese credit card users or customers from April 2005 to September 2005. The dataset employs the binary variable `default.payment.next.month` as the response variable, indicating whether or not the credit card holders are defaulters next month.

## Attributes of the Dataset 📋
- **ID:** ID of each client
- **LIMIT_BAL:** Amount of given credit in NT dollars
- **SEX:** Gender
- **EDUCATION:** Level of education
- **MARRIAGE:** Marital status
- **AGE:** Age in years
- **PAY_[0-6]:** Repayment status from April to September, 2005
- **BILL_AMT[1-6]:** Billed amount from April to September, 2005
- **PAY_AMT[1-6]:** Previous payment done from April to September, 2005
- **default.payment.next.month:** Default payment (1 = yes, 0 = no)

## Usage Instructions 📝
1. Clone the repository.
2. Download the dataset from the provided URL.
3. Prepare your Python environment with necessary libraries.
4. Run the provided scripts for data preprocessing, model training, and evaluation.

## Conclusion 🎉
This analysis aims to provide financial institutions with insights into predicting credit card defaults, enabling proactive risk management and decision-making. By leveraging machine learning techniques on historical data, institutions can mitigate losses and optimize credit card issuance strategies.
