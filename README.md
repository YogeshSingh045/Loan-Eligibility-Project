# Loan-Eligibility-Project

🏦 Loan Eligibility Prediction

📌 Project Overview

This project builds a machine learning model to predict whether a loan should be approved based on applicant information such as income, education, employment, and credit history.

📊 Dataset: Provided in CSV format, contains 614 loan applications

🎯 Goal: Help a financial institution automate and optimize loan approval decisions

🧰 Tools & Technologies Used
Python (Pandas, NumPy)

Scikit-learn

Matplotlib & Seaborn

Google Colab

🔍 Exploratory Data Analysis (EDA)

Identified missing values and imputed using mean/mode

Created new features like Total_Income, LoanAmount_log, Total_Income_log

Explored relationships between:

Income & loan amount

Education & applicant income

Credit history & loan approval rate

📊 Example Plots:

Histogram of applicant/coapplicant income

Loan approval by credit history

Boxplot of loan amounts by education level

⚙️ Data Preprocessing

Imputed missing values using domain-appropriate strategies

Encoded categorical features using LabelEncoder

Feature scaled using StandardScaler

Combined features to enhance prediction quality:

Total_Income = Applicant + Coapplicant

LoanAmount_log to normalize skewed distribution

🤖 Model Building
Trained two models:

Model	Accuracy
Decision Tree	67.4%
Naive Bayes	84.5% ✅ Best

