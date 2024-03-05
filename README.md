# Lending Club Case Study
> Intention is to understand how consumer attributes and loan attributes influence the tendency of default.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Lending Club Case study conatains Loan dataset having different attributes pertaining to the domain of Loans.

- The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for 
  taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

- To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

- Loan Data Set 


## Conclusions
-> ### Insights 1: Univariate Analysis 

Numerical  Univariate Analysis: 

- Loan amount is varying from 2000 to 14000 but the highest loan amount borrowed is between 4000 to 6000 and 8000 to 12000
- Highest Amount funded by inveestors at the time ranges between 4000 to 12000
- Maximum terms for the loan is 35 to 36 months
- Maximum Interest rate varying between 6 to 16.5 in that highest rate of interest ranges between 6 to 7.5 and 10.5 to 11.5
- Maximum number of instalments for the loan is less than 400
- Maximum annual income of the borrowers is 30000 to 60000
- Total payment wrt loan amount is less than 10000 


 Categorical Univariate Analysis:

- B Grade borrower's are more than other grades
- A4 subgrade borrower's are more compare to other 
- 10+ years is the maximum employment length of borrowers
- Maximum borrower's home ownership is RENT
- Verification status for most of the loan given is not verified
- Most of the borrower's has takenn loan for the purpose of debt_consolidation


-> ### Insights 2: Bivariate Analysis:

  Categorical variables wrt Charged Off:

- People under Grade B and subgrade B5 are the most likely to default
- Those who are leaving on Rent are mostly likely to default
- Most people do not have their income surces verified
- `Debt Consolidation` is the foremost purpose for defaulting the loan


  Numerical Vs Charged Off:

- Most people have annual income between 20k to 40k
- 5k to 15k is the loan amount given to the majority people who are defaulting
- interest rate is 11 to 17 for those under charged off category
- Maximum people got the term of 36 months 
- dti ratio lies between 10 to 20 in this scenario
- installment amount is rupees 200 to 400 for the defaulted ones
- The trend of inquiry last 6 months is 0 for most and is constantly droping 
- 0 to 10k is the range of total payments that defaulted borrowers are having
- Maximum number of defaults occured when the loan was issued in Dec in the year 2011


# Observations:

### The analysis shows the probability of defaulting when:

- People who has taken loan for `home improvement` and have income of 60k to 70k
- People whose home ownership is `MORTGAGE` and have income 60k to 70k
- People whose interest rate is greater than 12% and have income of 60k to 120k
- Who defaulted the most has taken loan amount of 12k to 14k for `small business purpose`
- loan amount of 25k to 30k with greater than 15% of interest rate
- People whose home ownership is `MORTGAGE` has loan amount of `10k to 12k`
- When grade is 'F' with loan amount of 15k to 17.5k
- Whose work experience is '10+ years' and have loan amount of 10k to 12k
- Verification done only for heigher loan amount with 14k to 16k


## Technologies Used

- Python on Jupyter Notebook
- Libraries: Numpy, Pandas, MatplotLib, Seaborn


## Contact
Created by: @Sourav-sharma9693
            @sana2403   
