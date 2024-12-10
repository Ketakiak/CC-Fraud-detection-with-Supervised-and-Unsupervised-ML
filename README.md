# CC Fraud detection with Supervised and Unsupervised ML

# Problem Statement
The Credit Card Classification Project is a machine learning project focused on classifying credit card transactions into 2 different categories. This system is designed to help identify and categorize credit card transactions accurately. I have used both supervised and unsupervised ml algorithms.

# Overview
Credit card fraud detection is a critical application in the financial industry to prevent unauthorized transactions and protect customer assets. This project employs machine learning algorithms to classify transactions as either fraudulent or legitimate based on features derived from transaction data.

The solution includes the following steps:

Data preprocessing, including handling class imbalance with techniques like SMOTE (Synthetic Minority Oversampling Technique).
Exploratory Data Analysis (EDA) to understand patterns in the data.
Training machine learning models like Logistic Regression and Xtreme Gradient Boosting.
Model evaluation using metrics like Accuracy, Precision, Recall, F1-score, and AUC-ROC.

# More about Credit Score with ML
The project is implemented in a Jupyter Notebook, using the Python programming language and several popular machine learning libraries such as NumPy, Pandas, Matplotlib, and Seaborn. The data used in this project is a simulated dataset of individuals and their credit scores, which I use to train and evaluate several different machine learning models mainly focused on Logistic Regression and XGBoost model. For unsupervised, anomly detection using Isolation forest is used.

# Features
Data Preprocessing: Scaling, missing value imputation, and class balancing.

EDA: Insights into transaction patterns and fraud trends.

Model Training: Supports Logistic Regression, Random Forest, and XGBoost.

Hyperparameter Tuning: Grid search and cross-validation.

Evaluation: Metrics include precision-recall and AUC-ROC curves.



# Download the data from this link
[https://www.kaggle.com/datasets/jacklizhi/creditcard](url)

This dataset contains anonymized features, with the target variable indicating fraudulent (1) or legitimate (0) transactions.

Rows: 284,807
Features: 30 (28 anonymized features, Amount, and Time)
Target variable: Class


Happy coding!
