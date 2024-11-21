# **Customer Churn Prediction Using Python**

## **Overview**
This project predicts customer churn for a telecom company by leveraging machine learning techniques and exploratory data analysis (EDA). The goal is to identify customers likely to churn and provide actionable insights for business strategies.

---

## **Project Workflow**

### **1. Dataset Loading and Exploration**
- **Dataset**: `Telco_customer_churn.csv`.
- Initial exploration conducted to understand features and identify patterns.

### **2. Data Cleaning and Preprocessing**
- Removed irrelevant columns (e.g., `CustomerID`).
- Handled missing values by dropping incomplete rows.
- Encoded categorical variables to ensure compatibility with machine learning algorithms.

### **3. Exploratory Data Analysis (EDA)**
- Visualized the churn distribution for insights.
- Created a correlation heatmap to analyze relationships between numerical features.

### **4. Model Building**
- **Algorithm**: Trained a Random Forest Classifier to predict churn.
- Tuned hyperparameters to improve model performance.

### **5. Model Evaluation**
- Evaluated performance using metrics: **accuracy**, **precision**, **recall**, and **F1-score**.
- Analyzed results with a confusion matrix for deeper insights.

---

## **Key Results**
- **Accuracy**: Achieved a high accuracy rate using the Random Forest Classifier.
- **Insights**: Identified key factors contributing to churn, such as **contract type** and **monthly charges**.

---

## **Technologies Used**
- **Python Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.
- **Tools**: Jupyter Notebook, `joblib` (for saving the trained model).

---

## **Files in the Repository**
- **Customer_Churn_Prediction_Notebook.pdf**: A complete project notebook saved as a PDF.
- **Telco_customer_churn.csv**: Dataset used for this project.

--- 

This repository provides a structured approach to tackling customer churn prediction, offering practical insights and a reproducible workflow.
