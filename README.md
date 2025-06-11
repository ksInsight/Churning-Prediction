💼 Bank Customer Churn Prediction
A Machine Learning Project to Predict Customer Attrition in Banks

📌 Overview
This project focuses on identifying potential bank customers who are likely to churn (i.e., leave the bank) using machine learning models. Churn prediction is a vital tool in customer relationship management as retaining an existing customer is far more cost-effective than acquiring a new one.

Built using Python in Google Colab, this project walks through a complete data science pipeline—from understanding the data to deploying a classification model.

🧠 Objective
The main objective of this project is to predict whether a customer will leave the bank or not based on various features like age, balance, tenure, and activity status. The final outcome helps banks:

Target at-risk customers

Improve customer retention strategies

Optimize marketing and service delivery

🗂️ Dataset
The dataset used is commonly referred to as the "Bank Churn Modeling Dataset" and includes the following:

Total Rows: 10,000 customers

Target Variable: Exited (1 if the customer left the bank, 0 otherwise)

🔑 Key Features:
Feature	Description
CreditScore	Customer credit score
Geography	Country of residence
Gender	Male/Female
Age	Age of the customer
Tenure	Number of years with the bank
Balance	Account balance
NumOfProducts	Number of bank products used
HasCrCard	Has credit card (1 = yes, 0 = no)
IsActiveMember	Activity status
EstimatedSalary	Customer's estimated annual salary

🛠️ Technologies & Tools
Python

Google Colab

Pandas for data handling

NumPy for numerical operations

Matplotlib & Seaborn for data visualization

Scikit-learn for machine learning algorithms

🔄 Workflow
1. Data Preprocessing
Dropped irrelevant columns (RowNumber, CustomerId, Surname)

Handled categorical variables (Gender, Geography) using encoding

Standardized numerical features using StandardScaler

Split data into train-test sets

2. Exploratory Data Analysis (EDA)
Distribution plots for churn vs non-churn

Correlation heatmaps

Boxplots and countplots for key variables

3. Model Building & Evaluation
Trained multiple ML classification algorithms:

Logistic Regression

K-Nearest Neighbors

Decision Tree Classifier

Random Forest Classifier

Evaluation metrics:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

ROC-AUC Curve

🏆 Results
The Random Forest Classifier achieved the best performance with:

Accuracy: ~86%

Precision: High for both churn and non-churn classes

ROC-AUC Score: Above 0.85

Top predictive features included:

Age

Balance

Number of products

IsActiveMember

📈 Visuals
The project includes visual representations for:

Class imbalance

Feature correlation

Model performance comparison

Confusion matrices and ROC curves

✅ Conclusion
This minor project successfully demonstrates how machine learning can be applied to predict customer churn in a banking environment. By identifying at-risk customers, banks can proactively engage them and reduce attrition rates.

🧑‍💻 Author
Kiran Singh
A data enthusiast currently exploring applications of machine learning in real-world domains like finance and healthcare.
Feel free to reach out if you want to collaborate or ask questions!
