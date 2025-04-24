# Customer Churn Prediction

This project uses machine learning to predict customer churn for a telecom company using the Telco dataset. The goal is to identify at-risk customers early and suggest business strategies to reduce churn.

---

## Key Objectives
- Predict churn using classification models (Logistic Regression, Random Forest, XGBoost)
- Explore top drivers of churn through visualizations and model insights
- Improve performance using SMOTE for class imbalance
- Evaluate final model with ROC curve and business-friendly visuals

---

## Visual Insights

### Churn by Contract Type
Customers with month-to-month contracts churn significantly more often than those on 1- or 2-year plans.  
![Churn by Contract](Churn%20by%20Contract%20Type.png)

---

### Tenure by Churn
Customers who churn tend to leave earlier — often within the first year of service.  
![Tenure by Churn](Tenure%20by%20Churn.png)

---

### ROC Curve – XGBoost + SMOTE
Strong performance (AUC = 0.80) — this curve shows the model's ability to distinguish between churn and no churn.  
![ROC Curve](ROC%20Curve%20(XGBoost%20+%20SMOTE).png)

---

### Confusion Matrix & Classification Report
Model performance shows balanced accuracy and improved recall with SMOTE.  
![Classification Report](SXGBoost%20+%20SMOTE%20Confusion%20Matrix%20&%20Classification%20Report.png)

---

## Final Model Performance
- Model: XGBoost + SMOTE
- Accuracy: 76.6%
- Recall (Churn): 58%
- AUC Score: 0.80

---

## Tools Used
- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn, XGBoost, imbalanced-learn (SMOTE)
- Google Colab

---

## Dataset
- Telco Customer Churn Dataset (Kaggle): https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

## Business Takeaway
Customers who are new, on month-to-month plans, and paying higher monthly charges are most at risk of churning. Focus retention strategies on this segment.
