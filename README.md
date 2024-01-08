# Lending Club Case Study
- This project revolves around risk analytics in the largest online loan marketplace, where the primary objective is to minimize credit losses incurred from lending to risky applicants. The company, offering personal loans, business loans, and medical procedure financing, faces financial setbacks primarily from borrowers labeled as 'charged-off' or defaulters. The project's focus is on identifying driving factors, or driver variables, behind loan defaults through exploratory data analysis (EDA). By understanding these indicators, the company aims to reduce risky loans, thereby cutting down on credit losses. This knowledge will be instrumental for informed portfolio management and risk assessment, enhancing the overall financial health of the lending institution.


## Table of Contents
* General Information
* Conclusions
* Python Library Used for Analysis


## General Information
- **Project Overview:** This project focuses on risk analytics in the largest online loan marketplace, aiming to minimize credit losses by identifying factors indicating loan default. The company seeks to understand the variables strongly associated with defaulting borrowers, enabling better portfolio management and risk assessment.
- **Background:** Operating in the financial domain, the company provides online loans, facing challenges of credit losses from defaulted loans. The project leverages exploratory data analysis (EDA) to discern patterns and variables predicting loan default.
- **Business Problem:** The core business problem is identifying risky loan applicants to reduce credit losses. The project targets understanding variables strongly linked to loan default, specifically those labeled as 'charged-off,' improving lending decisions.
- **Dataset Used:** While specifics about the dataset are not provided, it likely includes loan and borrower information, facilitating the identification of patterns and correlations indicative of potential loan default.



## Conclusions
- Conclusion from the **Univariate Analysis**
    - Loan Status
        - 82.96 % loans were fully paid.
        - 14.17 % loans were charged off.
        - 2.89 % loans were current.
        
    - Purpose of Loan
        - Most of the loans taken for debt consolidation(47%)
        - Second one is Credit card bill payment (13%)
    - Loan Amount
        - Most of the Loan amounts are in range of 5000 - 15000.
    - Interest Rate
        - Most of the interest rates are in range of 9 % - 14.5 %.
    - Annual Income
        - Most of the borrower's Annual incomes are in range of 40000 - 82000.
    - Loan approved rate per year
        - Number of loan application is increasing every year
    - Annual Income Vs Charged off
        - Income range 80000+ has less chances of charged off.
        - Income range 0 - 20000 has high chances of charged off.
        - Annual in come is inversely proportional charged off.

- Conclusion from the **Bivariate Analysis**
    - Purpose of Loan Vs Charged off
        - Small Business applicants have high chances of getting charged off.
    - Grade Vs Charged off
        - Grade "A" has very less chances of charged off.
        - Grade "F" and "G" have very high chances of charged off.
        - Chances of charged off is increasing with grade moving from "A" towards "G".



## Python Library Used for Analysis
- Numpy - version 1.26.3
- pandas - version 2.1.4
- matplotlib - version 3.8.2
- seaborn - version 0.13.1



## Contact
Created by [@arunjames003](https://github.com/arunjames003) - feel free to contact me!
