# Mini_Project_Pycaret
This mini-project focuses on predicting Customer Churn using the Telco Customer Churn dataset. PyCaret’s classification module is used for automated model comparison, evaluation, and visualization. A **Logistic Regression model** was trained and evaluated using confusion matrix and ROC-AUC metrics.

# 🚀 Project Highlights

- Automated ML pipeline using PyCaret Classification

- Data cleaning, preprocessing & categorical encoding handled automatically

- Logistic Regression applied as one of the main models

- Evaluation using:

  - Confusion Matrix

  - ROC & AUC curves

- Streamlit UI for interactive model visualization

# Confusion Matrix for Logistic Regression
![Confusion Matrix](Linear_Regression_confusion_Matrix.png)

# ROC Curves for Logistic Regression
![ROC Curve](ROC_Curve.png)

# 📂 **Dataset:** [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

# 🚀 How to Run the Code
pip install -r requirements.txt

streamlit run churn.py

python -m streamlit run churn.py
