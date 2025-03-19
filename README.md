# Bank-Loan-Default-Risk-Analysis  
**Overview**  
  This project performs Exploratory Data Analysis (EDA) on bank loan application data to analyze loan default risks. The goal is to identify patterns that indicate if a client has difficulty repaying their installments, which can help financial institutions make better lending decisions.  

**Business Understanding**  
  Loan providers face challenges in approving loans due to applicants' insufficient or non-existent credit history. Some consumers exploit this by defaulting on loans. This project analyzes the patterns in loan data to ensure that applicants capable of repaying the loan are not rejected while minimizing financial loss from defaulters.  

**Business Objective**  
  The objective of this analysis is to identify high-risk applicants based on past data, helping financial institutions make informed lending decisions. This could include actions such as denying the loan, reducing loan amounts, or adjusting interest rates based on risk levels.  

**Features**  
-Data cleaning and preprocessing  
-Handling missing values  
-Exploratory data analysis (EDA)  
-Data visualization  
-Correlation analysis  
-Standardizing values and feature engineering  

**Installation**  
  To run this project, you need to have Python and Jupyter Notebook installed. You can install the required dependencies using the following command:  
  pip install pandas numpy matplotlib seaborn missingno  

**Dependencies**  
The project requires the following Python libraries:  
-Pandas  
-NumPy  
-Matplotlib  
-Seaborn  
-Missingno  
-Dataset  

The dataset used in this analysis includes:  
-application_data.csv: Contains loan applicant details.  
-previous_application.csv: Contains data on previous loan applications.  

**Data Cleaning**  
-Checked and visualized missing values using missingno.  
-Identified and removed columns with more than 40% missing values.  
-Standardized numerical features such as converting negative days into positive values.  
-Binned income amounts into categories to analyze loan eligibility trends.  

**Exploratory Data Analysis**  
-Visualized missing data distribution.  
-Analyzed correlations between different features and target variable.  
-Assessed applicant details such as contact availability, family members, and region ratings.  

**Results**  
-Identified key factors affecting loan defaults.  
-Found significant correlations between external sources and loan repayment.  
-Binned income data to observe default rates based on salary ranges.  
