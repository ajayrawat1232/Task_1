## 📊 Task_1: Data Cleaning and Preprocessing – Marketing Dataset
## 📌 Project Summary
This project demonstrates comprehensive data cleaning and preprocessing techniques using Pandas and Scikit-learn, applied to a marketing customer dataset. It's part of a broader data science pipeline that prepares raw customer data for machine learning modeling and insights generation.

## 📂 Dataset Description
The dataset contains detailed information on customer demographics and behavior, including:

Demographics: year_birth, education, marital_status, income

Purchase History: mntwines, mntfruits, mntmeatproducts, etc.

Web & Store Interaction: Various metrics reflecting digital and in-store engagement

Campaign Responses & Customer Feedback: Including complaint records and campaign outcomes

## 🔧 Core Tasks Completed
## ✅ Data Cleaning
Renamed all columns to follow the lowercase_snake_case convention for consistency

Converted dt_customer into proper datetime format

Cast education and marital_status columns to categorical types

Detected and handled missing values effectively

## ✅ Feature Engineering
Added a new column customer_days representing the number of days since customer enrollment

Removed irrelevant or redundant features: id, dt_customer, z_costcontact, z_revenue

## ✅ Data Export
Final cleaned and transformed dataset saved as: processed_data.csv

## 🧪 Tools & Libraries Used
pandas
numpy
scikit-learn

