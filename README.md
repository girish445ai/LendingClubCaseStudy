# Project Name:Lending club case study
This project is about the lending club, which gives us the basic idea about how real life business problems are solved using EDA,in this case study ,apart from applying the techniques learnt in EDA,we’ll also develop a basic understanding of risk elements in banking and financial services and also come to a conclusion of how to minimize the risk of losing money with the insights obtained using visualization plots.

## General Information
### Assignment Brief:


You work for a consumer finance company Lending Club which specialises in lending various types of loans to urban customers. This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. When a person applies for a loan, there are two types of decisions that could be taken by the company:


Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Business Objectives:
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.

Objective is to identify the risky loan applicants at the time of loan application so that such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment. And thus minimise the risk of losing money while lending to customers.
## Data set:
The Loan Data provided by the Lending Club consists of information in the time period 2007 to 2011

Data dictionary describing the meaning of each variable is provided.

## Conclusions
- Key driver features that increases or decreases the defaulters are :

-Term: Charged-off rate increases when term increases.
-Annual Income: Borrowers with lower annual income are likely to default.
-Interest Rate: Charged off rate increases when interest rate increases.
-Purpose: Charged off rate increases when purpose is small business.
-dti: Charged off rate increases when dti increases.
-revol_util: Charged off rate increases when revolve util increases.


## Technologies Used
- library - Numpy
- library - Pandas
- library - Seaborn