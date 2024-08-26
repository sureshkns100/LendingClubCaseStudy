# Project Name
> Outline a brief description of your project.


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

####### Minor Impact of the reason for Loan Default ########

.Higher loan amount (above 16K)

•Higher installment amount (above 327)

•Lower annual income (below 37K)

•Higher debt to income ratio (above 15%)

•Applicant’s address state (NV, SD, AK, FL, etc.)

•Loan issue month (Dec, May, Sep)

- Conclusion 2 from the analysis

####### Heavy Impact of the reason for Loan Default #########

•Higher interest rate (above 13%)

•Higher revolving line utilization rate (above 58%)

•Repayment term (5 years)

•Loan grade & sub-grade (D to G)

•Missing employment record

•Loan purpose (small business, renewable energy, educational)

•Derogatory public records (1 or 2)

•Public bankruptcy records (1 or 2)

- Conclusion 3 from the analysis
######## Combined Impact of the reason for Loan Default #########

•High loan amount & interest rate for lower income group

•High installment and longer repayment term

•Home ownership (other) and loan purpose (car, moving or small business)

•Residential state and loan purpose

•Income group and loan purpose

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
import warnings
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats
from IPython.core.display import HTML
%matplotlib inline
warnings.filterwarnings('ignore') # if there are any warning due to version mismatch, it will be ignored

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