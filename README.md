# -Loan-Eligibility-Prediction-App-
The Loan Eligibility Prediction App is a web tool that uses machine learning to evaluate loan eligibility. By analyzing inputs like age, income, and loan amount, the app employs a decision tree model to provide instant predictions on loan approval, offering users quick insights into their eligibility.

## Table of Contents

- [Introduction](#introduction)
- [Business Question](#business-question)
- [Topics Covered](#topics-covered)
- [Interpreting Results](#interpreting-results)
- [Requirements](#requirements)
- [Running the Application](#running-the-application)
- [License](#license)

## Introduction

The Loan Eligibility Prediction App is a web application designed to help users assess their eligibility for loans based on various financial and demographic factors. By leveraging machine learning techniques, this application provides users with insights and predictions regarding their loan applications.

## Business Question

The primary business question addressed by this project is: **"What factors influence an individual's eligibility for a loan?"** This project aims to provide valuable insights to both applicants and financial institutions regarding the criteria that affect loan approvals.

## Topics Covered

1. **Descriptive Statistics**: 
   - Analyzed the dataset to summarize the main characteristics of the loan applicants, including age, income, and loan amount.

2. **Data Visualization**: 
   - Created visual representations of the data, including histograms and boxplots, to understand the distribution of features and the relationship between income and loan eligibility.

3. **Decision Tree Prediction Model**: 
   - Developed a decision tree model to predict loan eligibility based on applicant features. This model helps in understanding the decision-making process for loan approvals.

4. **Flask App to Check Eligibility**: 
   - Built a user-friendly Flask web application that allows users to input their age, income, and loan amount to predict their eligibility for a loan.

## Interpreting Results

The application provides the following insights based on the data:

- **Histograms** reveal the distribution of age, income, loan amount, and eligibility status among applicants.
- **Boxplots** illustrate the correlation between income and loan eligibility, showing that eligible applicants generally have higher incomes compared to ineligible ones.
- **Summary Statistics** indicate that approximately 29.5% of applicants are eligible for loans.

### Sample Outputs

- **Flask Application**:

![image](https://github.com/user-attachments/assets/cf7d1bc0-07bd-441b-a01b-6b0a02eb9661)
![image](https://github.com/user-attachments/assets/5c03278e-49a7-46e1-a6c9-b7f3613cb12c)



- **Histograms**:
 ![image](https://github.com/user-attachments/assets/4c7a2d11-e6c7-4c18-88d3-c25926abc193)

  - Age, income, and loan amount distributions.
  
- **Boxplot**:
 ![image](https://github.com/user-attachments/assets/11bd8c1e-725b-4e43-bd49-f4a01ca5b196)

  - Income vs. Loan Eligibility.

- **Summary Statistics**:
  | Metric    | Age         | Income       | Loan Amount | Eligible   |
  |-----------|-------------|--------------|-------------|------------|
  | Count     | 1000.0     | 1000.0      | 1000.0      | 1000.0     |
  | Mean      | 38.75      | 69785.69     | 27816.92    | 0.295      |
  | Std Dev   | 12.19      | 28440.13     | 12771.70    | 0.46       |
  | Min       | 18.0       | 20060.0      | 5097.0      | 0.0        |
  | 25%       | 28.0       | 46114.5      | 16431.5     | 0.0        |
  | Median    | 40.0       | 69210.5      | 28562.0     | 0.0        |
  | 75%       | 50.0       | 95215.5      | 38413.25    | 1.0        |
  | Max       | 59.0       | 119986.0     | 49976.0     | 1.0        |

## Requirements

Flask==2.0.3
scikit-learn==1.0
pandas==1.3.3
numpy==1.21.2
matplotlib==3.4.3
seaborn==0.11.2
pickle5==0.0.11 

