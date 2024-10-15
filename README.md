Customer Churn Prediction Project


This project focuses on predicting customer churn using machine learning techniques. The dataset used in this project is obtained from Kaggle and contains information about customer demographics, services subscribed to, account details, and churn status.

About the Dataset


Context

The dataset is aimed at predicting customer behavior to facilitate the development of effective customer retention strategies. By analyzing relevant customer data, businesses can identify patterns and factors contributing to churn, allowing them to tailor retention programs accordingly.

Content

Each row in the dataset represents a unique customer, while columns contain various attributes such as:

Churn: Indicates whether the customer left within the last month.

Services: Details about services subscribed to, including phone, internet, online security, etc.

Account Information: Information about the customer's account, including tenure, contract type, payment method, etc.

Demographics: Gender, age range, and whether the customer has partners and dependents.

Objective

The primary objective of this project is to develop a predictive model that can accurately forecast whether a customer is likely to churn or not. By leveraging machine learning algorithms on historical customer data, we aim to identify key factors influencing churn and provide actionable insights for customer retention.

Approach

Data Preprocessing: Cleaning and preparing the dataset for analysis, handling missing values, encoding categorical variables, and feature scaling.

Exploratory Data Analysis: I did a deep dive to understand and generate insight from the data. I looked at different insights like churn rate, risk ratio, correlation, mutual information, etc.

Model Building: Training and evaluating various machine learning models for churn prediction. Logistic Regression, XGBoost and TensorFlow were used to make the prediction.

Model Evaluation and Optimization: Assessing model performance using AUC-ROC evaluation metrics. Fine-tuning hyperparameters to improve model metric and generalization.

Dependencies

Python 3

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, XGBoost, TensorFlow.

Usage

Clone the repository to your local machine.

Install the required dependencies using pip install -r requirements.txt.

Run the Jupyter notebook to execute the analysis and model building process.

Contribution

Contributions to this project are welcome! If you have any suggestions, bug fixes, or enhancements, feel free to open an issue or submit a pull request.

Acknowledgments

Dataset Source: [Kaggle - Customer Churn Prediction](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Inspired by IBM Sample Data Sets
