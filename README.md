📉 Customer Churn Prediction








📌 Project Overview

This project analyzes a customer churn dataset to uncover the key factors driving customer attrition and to build a robust machine learning model for predicting churn. The results provide actionable insights that support data-driven customer retention strategies and revenue protection.

🎯 Problem Statement

Customer churn poses a significant challenge to business sustainability. This project aims to:

Understand customer behavior patterns associated with churn

Identify the most influential churn predictors

Build a reliable classification model to detect high-risk customers early

📂 Dataset

The dataset includes customer usage and service-related attributes such as:

Day, evening, night, and international call charges

Number of customer service calls

International and voicemail plan indicators

Churn status (target variable)

🛠️ Project Workflow

Data Cleaning & Preparation

Handled missing values and corrected data types

Removed redundant and non-informative features

Exploratory Data Analysis (EDA)

Examined churn distribution

Analyzed usage patterns and service interactions

Visualized correlations and trends

Feature Importance Analysis

Identified the strongest drivers of churn

Model Development

Trained a Random Forest classification model

Model Evaluation

Evaluated using accuracy, recall, and confusion matrix

Emphasized recall to improve churner detection

🔍 Key Insights

Total Day Charges, Customer Service Calls, and International Plan are the most influential churn predictors

Customers with high usage and frequent service interactions have a higher likelihood of churn

The Random Forest model demonstrates strong predictive performance and stability

📈 Recommendations

Enhance customer service quality for frequent callers

Engage international plan subscribers through competitive analysis and proactive communication

Offer loyalty incentives to high-spending customers

Deploy the Random Forest model to prioritize high-risk customers effectively

🧰 Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📁 Repository Structure
├── data/                # Dataset files
├── churn_analysis.ipynb # Main notebook (EDA + modeling)
├── README.md            # Project documentation

▶️ How to Run

Clone the repository:

git clone https://github.com/your-username/customer-churn-prediction.git


Open the notebook:

jupyter notebook


Run all cells to reproduce the analysis and results

✅ Results

The final Random Forest model achieves high accuracy and strong recall, making it effective at identifying customers at risk of churn and supporting targeted retention strategies.

🧠 Conclusion

This project demonstrates the practical application of data analysis and machine learning in solving real-world business problems. The insights and predictive model provide a solid foundation for deploying churn prediction systems in production environments.

📌 GitHub Repository Description (Short)

Machine learning project using Random Forest to analyze customer churn, identify key churn drivers, and support data-driven retention strategies.

👤 GitHub Profile / Portfolio Summary

Customer churn prediction project leveraging exploratory data analysis and machine learning to uncover churn drivers and build a high-performing Random Forest classifier for proactive customer retention.
