# Customer Churn Prediction System

## 📌 Project Overview
This project is part of **Machine Learning Task 2** assigned by **Future Interns**.  
The objective of this task is to build a **Customer Churn Prediction System** that identifies customers who are likely to stop using a service and present actionable insights through a **Power BI dashboard**.

The project combines **data preprocessing, classification modeling, and business visualization** to help organizations improve customer retention strategies.

---

## 🎯 Objectives
- Analyze customer behavior data
- Predict customer churn probability using machine learning
- Identify key factors driving customer churn
- Visualize churn insights in a business-friendly dashboard

---

## 🛠️ Tools & Technologies Used
- **Python**
  - Pandas
  - NumPy
  - Scikit-learn
- **Machine Learning Model**
  - Logistic Regression
- **Jupyter Notebook** – Data analysis & model building
- **Power BI Desktop** – Dashboard creation
- **GitHub** – Project hosting & version control

---

## 📂 Dataset
- **Dataset Name:** Telco Customer Churn Dataset (Public)
- **File Used:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- The dataset contains customer demographic details, service usage information, contract type, payment method, and churn status.

---

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing
- Loaded customer churn dataset using Pandas
- Handled missing values and data type issues
- Encoded categorical variables using one-hot encoding
- Removed non-informative columns

### 2️⃣ Model Building
- Split data into training and testing sets
- Trained a **Logistic Regression** classification model
- Applied feature scaling for better model convergence

### 3️⃣ Model Evaluation
- Evaluated model performance using:
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, and F1-score
- Generated churn probability for each customer

### 4️⃣ Power BI Dashboard
The Power BI dashboard includes:
- 🔢 **Overall Churn Rate**
- 🔢 **Average Churn Probability**
- 📊 **Key Churn Drivers** (Contract type, Internet service, Payment method)
- 📋 **High-Risk Customers Table**

---

## 📊 Dashboard Preview
![dashboard](https://github.com/user-attachments/assets/e4a94248-6ad8-4033-9465-c53071ef094d)


---

## 📁 Repository Structure
FUTURE_ML_02/
│
├── churn_prediction.ipynb        # Jupyter Notebook (ML workflow)
├── churn_predictions.csv         # Model prediction output
├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset
├── CHURN PREDICTION SYSTEM.pbix  # Power BI dashboard file
├── dashboard.png                 # Dashboard screenshot
└── README.md                     # Project documentation

---

## 📌 Key Insights
- Customers without long-term contracts have higher churn risk
- Fiber optic internet users show increased churn probability
- Electronic check payment method is strongly associated with churn
- Lack of online security services increases the likelihood of churn

---

## 🚀 Conclusion
This project demonstrates the application of machine learning techniques to predict customer churn and uncover key factors influencing customer behavior. The combination of predictive modeling and interactive visualization provides valuable insights that support data-driven decision-making for customer retention.

---

## 🙌 Acknowledgement
This project was completed as part of **Future Interns – Machine Learning Task 2**.  
The Telco Customer Churn dataset used in this project was sourced from Kaggle.
