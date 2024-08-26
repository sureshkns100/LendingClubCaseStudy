# Project Name  Lending Club Case Study - Suresh Narayanan/Yeshaswini J
> Outline a brief description of your project.

 A consumer finance company which specialises in lending various types of loans to urban customers.
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
Two types of risks are associated with the bank’s decision:
a) If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
b) If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
Business Understanding
You work for a consumer finance company which specialises in lending various types of loans to urban customers.
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
Two types of risks are associated with the bank’s decision:
a) If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
b) If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

- What is the business probem that your project is trying to solve?
The Company wants to understand the reason for the default of the Loan by the Customer with the analysis and that as inputs in deciding the approval/rejection of future Loan to the new customer applying for the Loan. Ex: The Variables which are the driving factor behind the default of Loan which will help the Company in their Portfolio and Risk Management.
- What is the dataset that is being used?
Loan Dataset

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis

1. Highly Influential Factors
These factors have a significant impact on the likelihood of loan default:

Interest Rate: Higher interest rates (above 13%) strongly correlate with increased default rates.
Revolving Line Utilization Rate: Utilization rates above 58% are strongly associated with higher default risks.
Repayment Term: Loans with a 5-year repayment term show a higher likelihood of default.
Loan Grade & Sub-Grade: Loans with grades and sub-grades from D to G have a notably higher default rate.
Missing Employment Record: The absence of an employment record significantly increases the risk of default.
Loan Purpose: Certain purposes like small business loans, renewable energy projects, and educational loans are linked with higher default rates.
Derogatory Public Records: Having 1 or 2 derogatory records raises the default risk.
Public Bankruptcy Records: The presence of 1 or 2 bankruptcy records is a strong indicator of potential default.

Conclusion 2 from the analysis

2. Moderately Influential Factors
These factors also impact the likelihood of default, though their effect is less pronounced than the highly influential factors:

Loan Amount: Larger loan amounts (above 16,000) are associated with higher default risk.
Installment Amount: Higher installment amounts (above 327) can increase the probability of default.
Annual Income: Lower annual incomes (below 37,000) contribute to a higher default risk.
Debt-to-Income Ratio: A higher debt-to-income ratio (above 15%) correlates with an increased likelihood of default.
Residential State: Certain states such as NV, SD, AK, FL, etc., show higher default rates.
Loan Issuance Month: Loans issued in December, May, and September tend to have higher default rates.

- Conclusion 3 from the analysis
3. Combined Impact Factors
These factors have an amplified effect on default risk when considered in combination:

High Loan Amount & High Interest Rate: Particularly risky for lower income groups. Combining a large loan amount with a high interest rate significantly increases default likelihood.
High Installment & Longer Repayment Term: A combination of high monthly installments and a longer repayment term can be particularly risky.
Home Ownership Status & Loan Purpose: Loans where home ownership is categorized as ‘other’ and purposes include car purchases, moving, or small businesses exhibit higher default risks.
Residential State & Loan Purpose: The interplay between the state of residence and the loan purpose influences default risk.
Income Group & Loan Purpose: The relationship between income levels and loan purposes can affect the likelihood of default.

The most critical factors influencing loan default include high interest rates, high revolving line utilization rates, long repayment terms, lower loan grades, missing employment records, and specific loan purposes. Additionally, larger loan amounts, higher installment payments, lower annual incomes, and higher debt-to-income ratios also contribute to default risk. Certain combinations of these factors, such as high loan amounts with high interest rates or high installments with longer terms, further amplify the risk.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
1. import warnings
2. import numpy as np
3. import pandas as pd
4. import matplotlib.pyplot as plt
5. import seaborn as sns
6. from scipy import stats
7. from IPython.core.display import HTML
8. %matplotlib inline
9. warnings.filterwarnings('ignore') # if there are any warning due to version mismatch, it will be ignored

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubsureshkns100] - feel free to contact me!
https://github.com/sureshkns100/Suresh-Narayanan-YeshaswiniJ-Lending-Case-Study


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
