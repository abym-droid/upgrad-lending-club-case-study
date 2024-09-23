# Lending Club Case Study
> We are given a dataset about a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

>The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- General Information/Background: This is an Upgrad case study project aimed to do EDA for a given dataset and report analysis results. The dataset is Loan dataset of a Consumer Finance Company, containing observations of past loan applicants who have fully paid or defaulted on loan. It also contains currently ongoing loans as well.
- Business Problem: The objective is to analyze patterns of loan default and report some key variables that could be used to  minimize loses in future for the company and also to increase revenue by not denying loans for certain positive behaviour patterns of individuals.
  
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
After a long process of analysis, we will conclude on few strong indicators/patterns for loan defaults. The associated rationale is also documented

1. **Interest Rate ('int_rate')**: Borrowers with higher interest rates are more likely to default. Lenders typically charge higher interest rates to borrowers with lower creditworthiness, which is often associated with a higher probability of default. Loans with interest rates above 15% (high-interest loans) are particularly risky and show a higher correlation with defaults.

2. **Loan Term ('long_term_loan')**: Borrowers with longer loan terms (60 months) are more likely to default compared to those with shorter loan terms (36 months). Longer loans carry more risk, as the borrower has to manage payments over a longer period

3. **Loan Purpose ('purpose')**: Small Business seem to be a likely risky category as individuals investing in small business (specially if for the first time) and seeking capital for it has a higher chance of failure in their business. 

4. **Revolving Utilization ('revol_util')**: High revolving credit utilization signals that the borrower is heavily reliant on available credit, which increases their risk of financial distress and default.

5. **Debt-to-Income Ratio ('dti')**: A higher debt-to-income ratio indicates that a borrower has a significant portion of their income dedicated to debt repayment (and less money available for additonal expenses or unforeseen circumstances), increasing their likelihood of default

6. **Credit Inquiries ('inq_last_6mths')**: In general if a borrower has high number of credit inquiries over a short period of time (6 months), it shows financial strain as they are trying to arrange for credit resulting in some financial institutions looking up their credit files.

7. **Loan Amount ('loan_amnt_category')**: Larger loans carry higher risks as it would generally carry higher interest rates and installments over longer term. Unless the borrower is of sound income, it is usually hard to manage larger loans.

8. **Loan Grade and Sub-Grade**: There is a high chance of loan defaults in Loan Grades F and G

9. **Address State**: It looks like borrowers from state 'NE' or Nebraska are most likely to default. Some more risky states are likely to be 'ID' (Idaho), 'NV' (Nevada), 'SD' (South Dakota)

10. **Income Category**: Low Income Category borrowers are most likely to default.

11. **Derogatory Public Records or Bankruptcies**: Defaulters are more likely to have either derogatory public records or public bankruptcies.


## Technologies Used
- library - Numpy
- library - Pandas
- library - Matplotlib
- library - Seaborn

## Acknowledgements
Give credit here.
- This project has contributions from Abhishek Shukla
- This project was based on subjects/topics taught by Upgrad Instructors based on Course 1 - Python for Data Science and Course 2 - Data Visualizations and EDA
- This project is also inspired by examples given and techniques taught by Upgrad Instructors Shivam Garg, Amit Pandey, Swapnil Desai and Tanisha Medewala


## Contact
Created by [@abym-droid] / abhim286@gmail.com - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
