# Data_Analysis_with_python
- For this project I used a dataset which contains details of various kind of customers of a telephone service 📞 📶
- For instance, fields like Customer ID, Gender,Tenure, PhoneService(yes/No), Churn(Yes or No) etc..

**Churn rate means the rate in which customers are leaving the particular service provider.**

**For this project we need to find th churn rates based on various features such as contract type, internet service type and monthly charges.**

A customer can leave a company because of so many reasons.
By analysing the huge data we can come across various factors that make the customer to leave.
For instance, based on their tenure, or if they are senior citizen or not, or if they have Tech support or if they had any issues with paper/paperless billing etc..
 ### Here are the steps the steps for this  project.
 Steps for the Project:
1. **Data Cleaning and Preprocessing:**
- Handle missing values (e.g., TotalCharges might have some blanks).
- Convert categorical data into numerical format using one-hot encoding or label
encoding.
- Standardize numerical columns (MonthlyCharges, TotalCharges).
- We need to standardize numerical columns so that we can compare them easily on a standardised scale.

2. **Exploratory Data Analysis (EDA):**
- Analyze churn rates by various features such as contract type, internet service type, and
monthly charges.
- Visualize data using charts (bar plots, histograms, box plots, etc.).
- Identify correlations between features using a heatmap.
3. **Feature Engineering:**
- Create new features (e.g., AverageMonthlySpend by dividing TotalCharges by
Tenure).
- Remove irrelevant or highly correlated features.

### What are the insights that I have drawn from this analysis 👇

- Total number of customers- 7043
- Churned Customers- 1869
- Churn rate is high for customers who are under Month-to-Month contract type.
- 




