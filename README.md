### Loan_prediction-EDA Project


---

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Dream Housing finance company data to help the company automate the loan eligibility process in real-time based on customer data obtained by filling the online application form. We use libraries like **Pandas, Numpy, Matplotlib, Seaborn**for cleaning, visualization, and analysis.

## Objective

The goal of this project is to:
1. Analyze **ApplicantIncome, Loan_Status, and Credit_History** across different Genders.
2. Detect Missing values in **Gender, Married Status, dependents, Credit_History and Self_Employed**.
3. Detect potential **outliers** in LoanAmount.
4. Provide recommendations for Loan Provider based on insights.


## Dataset

- **Loan_ID**               object
- **Gender**                object
- **Married**              object
- **Dependents**            object
- **Education**          object
- **Self_Employed**        object
- **ApplicantIncome**        int64
- **CoapplicantIncome**    float64
- **LoanAmount**         float64
- **Loan_Amount_Term**     float64
- **Credit_History**      float64
- **Property_Area**         object
- **Loan_Status**         object

## Steps and WorkFlow

### 1. Data Cleaning

- **Handle missing data**: Gender, Married Status, dependents, Credit_History and Self_Employed columns had null values.
- **Remove outliers**: LoanAmount 
- 
### 2. EDA (Exploratory Data Analysis)

1. **Frequency Distribution** of Loan_Status and Normalizing the value.
   
2. **Categorical Data distribution**: 
   - Visualized the count of each Gender, Married, Self_Employed and Credit_History distribtion using **bar plots**.
  
3. **Ordinal Data distribution**: 
   - Visualized the count of each Dependents, Education, Property_Area distribtion using **bar plots**.

   
### 3. Data Visualization

1. Visualize **ApplicantIncome** on Histogram using histplot.

2. Visually compare **income distributions** across different **education levels** using BoxPlot.

## Key Findings and Insights

1. Most of the applicants don't have any dependents. Around 80% are Graduate. Most applicants are from Semi-Urban area.

2. 80% applicants are male. Around 65% of applicants are married. Around 15% applicants are self employed. Around 85% applicants have repaid their debts.

3. Outliers in ApplicantIncome infer the Income disparity in the Society

4. Majority of co-applicant's income ranges from 0 to 5000. There are also a lot of outliers and are not Normally distributed.

## How to Run This Project
pip install pandas numpy matplotlib seaborn


