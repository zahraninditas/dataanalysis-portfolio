# 💳 FinanKu Credit Card Late Payment Prediction

## 📌 Problem Statement
There is a concern about late credit card payments at **FinanKu**, which can negatively impact the business.  
Therefore, it is necessary to predict customers with a high risk of late payment in order to design appropriate strategies to mitigate future risks.

## 🎯 Objective
Build a machine learning model that can predict **at least 60%** of customers who are likely to be late in credit card payments  
(Target: **Accuracy & Recall above 60%**).

## 📂 Dataset & Variables
The dataset consists of customer information with the following variables:

1. **Customer ID**: Unique customer identifier  
2. **Branch**: Customer branch location  
3. **City**: Customer city location  
4. **Age**: Customer’s age during the observation period  
5. **Avg. Annual Income/Month**: Average monthly income in one year  
6. **Balance (Q1–Q4)**: Quarter-end balance  
7. **Num of Products (Q1–Q4)**: Number of products owned at quarter-end  
8. **HasCrCard (Q1–Q4)**: Credit card ownership status  
9. **Active Member (Q1–Q4)**: Membership activity status  
10. **Unpaid Tagging**: Customer default (late payment) status  

## 🔬 Experiment Setup
- **Observation Period**:  
  - Last 12 months  
  - Last 6 months  

- **Feature Engineering**:  
  - Average balance across observation horizon, and balance change between start & end period  
  - Product ownership: average, max, and min  
  - Active membership calculated in months  

## 🛠 Tools & Skills
- **Python (Jupyter Notebook)** → Data cleaning, preprocessing, modeling  
- **Pandas, NumPy, Scikit-learn** → Feature engineering & machine learning  
- **Matplotlib, Seaborn** → Exploratory Data Analysis (EDA)  
- **Classification Models** → Logistic Regression, Gradient Boosting, Random Forest  

## 📈 Expected Outcome
- A predictive model with **Accuracy & Recall > 60%**  
- Identification of key factors influencing late payments  
- Insights to support business decision-making for credit risk management  
