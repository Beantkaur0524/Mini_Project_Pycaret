# Mini_Project_Pycaret
A mini machine-learning project for Customer Churn Prediction using PyCaret. The project includes data preprocessing, automated model comparison, and evaluation. A Logistic Regression model is also applied as a simple baseline to observe its behavior on churn data. 

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

📂 **Dataset:** [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

# 🚀 How to Run the Code
pip install -r requirements.txt

streamlit run churn.py

python -m streamlit run churn.py
