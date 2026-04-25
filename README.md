# Customer Churn Prediction

## Project Overview
This project predicts customer churn for a telecommunications company using machine learning.  
By identifying customers likely to leave, the company can take proactive actions to retain them, improving revenue and customer satisfaction.

---

## Dataset
- File: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- Source: [Kaggle: Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- Description: The dataset contains information about customer demographics, account information, subscribed services, and churn status.  
- Total Customers: ~7,000  
- Target Column: `Churn` (Yes/No)

---

## Project Structure
Customer-Churn-Prediction/
├── data/
│ └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── notebooks/
│ └── Customer_Churn_Prediction.ipynb
├── reports/
│ └── plots/ # Optional: visualizations
├── requirements.txt
├── README.md
└── .gitignore


---

## Methodology
1. **Data Preprocessing**
   - Handled missing values  
   - Encoded categorical variables (One-Hot / Label Encoding)  
   - Feature scaling for numeric columns  

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions of features  
   - Compared churn vs non-churn customers for key attributes  

3. **Model Training**
   - Logistic Regression  
   - Random Forest Classifier  
   - XGBoost Classifier  

4. **Evaluation Metrics**
   - Accuracy  
   - Precision, Recall, F1-score  
   - Confusion Matrix  
   - ROC-AUC Score  

5. **Feature Importance**
   - Analyzed key factors influencing churn (e.g., Contract type, Tenure, Monthly Charges, Internet Service)

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/Gowda487/customer-churn-prediction.git

Install dependencies:
pip install -r requirements.txt

Open and run the notebook:
jupyter notebook notebooks/Customer_Churn_Prediction.ipynb
Results

Model Accuracy: 86% (replace with your actual accuracy)
Key features influencing churn: Contract type, Tenure, Monthly Charges, Internet Service
Detailed plots and evaluation metrics are included in the notebook.
Future Work

Hyperparameter tuning to improve model performance
Deployment as a web app or dashboard

Handle class imbalance using techniques like SMOTE
Experiment with ensemble models or deep learning approaches

Libraries Used

pandas, numpy
matplotlib, seaborn
scikit-learn
xgboost
jupyter

Author
Bhuvan M Bhuvan M – Final Year Degree Student
GitHub: https://github.com/Gowda487
Email:bhuvanmbhuvanm15@gmail.com
