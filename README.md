# Project Name
    Lending Club is a consumer finance company that specialises in providing various types of loans to urban customers. One of the critical challenges we face is making accurate loan approval decisions. The challenges are two ways:
        Loss of Business: If they reject a loan application from an applicant who is likely to repay, they miss out on potential business opportunities. This not only affects our revenue but also their market competitiveness.
       
        Financial Loss: On the other hand, if they approve a loan for an applicant who is likely to default, they risk incurring massive financial losses. Defaults can lead to a loss of the principal amount and the interest, which affects their overall financial health.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Problem Statement
    Lending Club is a consumer finance company that specialises in providing various types of loans to urban customers. One of the critical challenges we face is making accurate loan approval decisions. The challenges are two ways:
    Loss of Business: If they reject a loan application from an applicant who is likely to repay, they miss out on potential business opportunities. This not only affects our revenue but also their market competitiveness.
    Financial Loss: On the other hand, if they approve a loan for an applicant who is likely to default, they risk incurring massive financial losses. Defaults can lead to a loss of the principal amount and the interest, which affects their overall financial health.
    
Objective
    The main objective is to identify patterns that indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. by using the (Exploratory Data Analysis )EDA on the dataset provided.

Understanding the Dataset
The data set contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns that indicate| if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of the loan, lending (to risky applicants) at a higher interest rate, etc.

When a person applies for a loan, two types of decisions could be taken by the company:

1. Loan Accepted: If the company approves the loan, there are three possible scenarios:
   Fully Paid: The applicant has fully paid the loan (the principal and the interest rate).
   Current: The applicant is in the process of paying the instalments, i.e., the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'. 
   Charged-off: The applicant has not paid the instalments in due time for a long period, i.e., he/she has defaulted on the loan.

2. Loan Rejected: The company rejects the loan because the candidate does not meet their requirements. Since the loan was rejected, there is no transactional history of those applicants with the company, and thus this data is not available in the dataset.

### Projet Information:
1.	Code Implementation:
        All the code for this project is written in one well-commented Python file. The comments explain each step of the process to make it easy to understand and follow.
2.	Insights and Observations:
        After analyzing the data, the key insights and observations are summarized in the code comments. These insights help identify which factors are most likely to influence loan defaults, offering valuable information for decision-making.
3.	Presentation of Results:
        Problem Statement & Approach: The presentation starts with a brief explanation of the problem Lending Club faces, which is making accurate loan approval decisions. It then provides an overview of the approach we took, which is using Exploratory Data Analysis (EDA) to find patterns in the loan data.
        Univariate and Bivariate Analysis Results: We explain the findings from the univariate and bivariate analysis in simple business terms. For example, we discuss how things like loan amount, annual income, and credit grade affect the chances of a loan defaulting.
        Visualizations: The presentation includes charts and graphs (like histograms and bar plots) to visually show the important findings from the analysis. These visuals help make the data easier to understand.
        Summary of Key Findings: Finally, the presentation wraps up by summarizing the most important insights from the analysis. This includes which factors are most likely to predict loan defaults and how Lending Club can use this information to improve their loan approval process.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Consider offering more long-term loans, as they have fewer defaulters compared to 36-month loans
- Be cautious with loans graded B, C, and D, as they have higher default rates. Strengthen the evaluation process for these grades.
- Be cautious with renters and those with mortgages, as they default more often.
- Ensure thorough verification, as verified applications have higher default rates.
- Be cautious with loans for debt consolidation, as they have the highest default rates. Use stricter criteria for these loans.
- Focus on applicants with debt-to-income ratios, as they default more. Use stricter criteria for these ratios.
- Be cautious with applicants earning $40K-$60K, as they default more. Do extra financial checks for this income range.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python version: 3.12.4
- Pandas version: 2.2.2
- Seaborn version: 0.13.2
- Numpy version: 1.26.4
- Matplotlib version: 3.8.4


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This case study required for the Executive PG Programme in Machine Learning & AI - UPGRAD and IIIT, Bangalore
- UpGrad tutorials on Data Visualisation and Exploratory Data Analysis (EDA) on the learning platform
- This project was based on Lending club loan data case study by www.upgrad.com


## Contact
Created by @LavanyaKumarV and Veenugopal T
- feel free to contact us!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
