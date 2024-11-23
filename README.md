# 🚢 Titanic Data Analysis: Comprehensive Data Cleaning and EDA | Data Science Portfolio
## 📋 Project Overview
This repository features a detailed analysis of the Titanic dataset, focusing on data cleaning, handling missing values, and exploratory data analysis (EDA). It provides a foundation for understanding data preprocessing techniques and uncovering valuable insights through visualization.  

## 📂 Repository Contents
titanic_eda.ipynb: A Jupyter Notebook containing all the steps for data cleaning, handling missing values, and performing EDA    
test.csv: The Titanic dataset used for this analysis. You can download the full dataset from Kaggle if not provided.  
README.md: This file contains a high-level overview of the project and its findings.   
## 📊 Key Insights
Age Distribution: Most passengers were between 20–40 years old, with a smaller proportion of children and elderly individuals.   
Survival Rate by Gender: Females exhibited a significantly higher survival rate compared to males.   
Survival Rate by Class: 1st-class passengers had the highest survival rate, while those in 3rd class faced the greatest risk.  
Fare and Age Relationship: Passengers paying higher fares tended to belong to older age groups, potentially indicating luxury travel.   
## 💡 Highlights
### Data Cleaning:
Missing values in the Age column were filled using the mean age.  
The Cabin column was highly sparse; missing values were replaced with "Unknown."  
Duplicates were checked and confirmed absent.  
### Exploratory Data Analysis:
Gender Distribution: Visualized using bar plots to illustrate the disparity between male and female passengers.  
Age Distribution: A KDE histogram provided insights into the age demographics of the passengers.  
Scatter Plot of Fare vs. Age: Highlighted trends between age and fare paid, with notable outliers.  
### Tools Used:
Pandas: For data manipulation and cleaning.  
Matplotlib & Seaborn: For creating compelling visualizations.  
