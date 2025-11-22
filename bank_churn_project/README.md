<h1 align="center">🔍 Bank Customer Churn Prediction</h1>

<p align="center">
  <b>End-to-end Machine Learning Project</b> — Data Cleaning | EDA | ML Models | Feature Importance | Insights  
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Data%20Analysis-Pandas%20%7C%20NumPy-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">
</p>

<hr>

# Bank Customer Churn Prediction

A complete end-to-end Data Science project to analyze customer behavior and predict churn (whether a customer will leave the bank).  
This project includes **EDA, preprocessing, model training, evaluation, feature importance, and dashboard insights**.

---

## Objective
To predict which customers are likely to churn based on demographic and account-related features.  
The project helps banks improve customer retention through data-driven decisions.

---

## Dataset Overview
- 10,000 customer records  
- Contains customer demographics, account info, and behavior  
- **Target variable:** Exited (1 = churn, 0 = stay)

### Key Features:
- CreditScore  
- Geography  
- Gender  
- Age  
- Tenure  
- Balance  
- NumOfProducts  
- HasCrCard  
- IsActiveMember  
- EstimatedSalary  

---

## Data Cleaning Performed
- Removed duplicate records  
- Standardized category values  
- Filled missing values  
- Encoded categorical columns  
- Scaled numerical columns  
- Created meaningful groups (e.g., TenureGroup)

---

## Exploratory Data Analysis — Key Insights
- Customers from **Germany** have the highest churn rate  
- **Older customers** are more likely to churn  
- Customers with **low activity** churn more  
- Customers with **only one product** have higher churn  
- **Balance** shows weak direct correlation with churn  
- **Inactive members** are high-risk and need attention  

---

## Model Building
Multiple machine learning models were trained:
- Logistic Regression  
- Decision Tree  
- Random Forest (Best Model)

### Best Model: Random Forest
The model showed strong performance in predicting churn, with:
- High ROC-AUC  
- Good Recall for identifying churners  
- Good overall performance after hyperparameter tuning  

Artifacts saved:
- Trained models (`.joblib`)  
- Confusion matrices  
- ROC comparison plots  
- Permutation importance results  
- Cleaned datasets  

---

## Feature Importance (Permutation Importance)
Top influential features:
1. **IsActiveMember**  
2. **Age**  
3. **NumOfProducts**  
4. **TenureGroup**  
5. **HasCrCard**

These features provide strong signals for churn prediction.

---

## Dashboard Summary (Excel)
The dashboard visualizes:
- Overall churn distribution  
- Geography-level churn analysis  
- Gender-wise churn  
- Tenure group analysis  
- Balance analysis  
- Customer activity impact  

This helps stakeholders quickly understand churn drivers.

---

## Conclusion
### Major churn drivers:
- Low account activity  
- Older age groups  
- Customers with fewer products  
- Country-based differences (Germany highest)

### Recommended Business Actions:
- Launch targeted retention campaigns  
- Personalized offers for high-risk customers  
- Improve engagement programs for inactive users  
- Encourage multi-product usage

---

## Tools & Technologies Used

| Category         | Tools |
|------------------|--------------------------------------------|
| Programming      | Python, Jupyter Notebook                   |
| Data Analysis    | Pandas, NumPy                              |
| Machine Learning | Scikit-learn, Joblib                       |
| Visualization    | Matplotlib, Seaborn, SHAP                  |
| Dashboard        | Microsoft Excel                            |
| Version Control  | Git, GitHub                                |

---

## Author
**Dabbikar Rakesh**  
GitHub: https://github.com/rakeshdabbikar4
(https://www.linkedin.com/in/rakesh-dabbikar/)








