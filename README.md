# Loan Approval Prediction Using Decision Trees

## 📌 Project Overview
This project applies the **Decision Tree algorithm** to predict whether a loan application will be approved based on various applicant details. It helps financial institutions automate the loan approval process.

## 📌 Dataset
- **Source:** [Loan Approval Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset)
- **Attributes:**
  - `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`: Applicant details  
  - `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`: Financial information  
  - `Credit_History`, `Property_Area`: Additional factors  
  - `Loan_Status`: Target variable (Approved/Not Approved)

## 📌 Project Steps

### 1️⃣ Data Collection & Loading  
- Loaded the dataset using Pandas.  
- Explored the dataset to check for missing values and data types.  

### 2️⃣ Data Preprocessing  
- Handled missing values by replacing them with the most frequent value.  
- Converted categorical variables into numerical format using **Scikit-Learn's `LabelEncoder`**.  

### 3️⃣ Splitting Data into Training & Testing Sets  
- Divided the dataset into **80% training** and **20% testing** to evaluate model performance.  

### 4️⃣ Implementing Decision Tree Algorithm  
- Trained a **Decision Tree Classifier** on the training dataset.  

### 5️⃣ Model Evaluation  
- Evaluated the model using **accuracy score** and a **classification report**.  
- Identified key performance metrics like precision, recall, and F1-score.  

## 📌 Conclusion & Key Insights
- The **Decision Tree model** helps automate loan approval decisions effectively.  
- **Categorical variables** were processed correctly to ensure accurate model training.  
- Financial institutions can use this model to **quickly assess loan applications**.  
