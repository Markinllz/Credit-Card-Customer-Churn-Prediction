# Credit-Card-Customer-Churn-Prediction
verview This project analyzes and predicts customer churn for a bank's credit card services using the BankChurners.csv dataset. The goal is to help the bank proactively identify customers likely to leave, so that targeted retention strategies can be implemented.


Features Used
Demographics: Age, Gender, Education Level, Marital Status, Income Category, Dependent Count
Product Info: Card Category, Credit Limit, Months on Book, etc.
All categorical features were encoded using OneHotEncoder or LabelEncoder as appropriate.




Workflow
Data Cleaning & Preprocessing
Removed unnecessary columns and handled missing values.
Encoded categorical variables using OneHotEncoder and LabelEncoder.
Normalized numerical features using StandardScaler.
Exploratory Data Analysis (EDA)
Analyzed class imbalance and feature distributions.
Visualized relationships between features and churn.
Modeling
Built machine learning pipelines using scikit-learn.
Trained and evaluated Logistic Regression and Random Forest models.
Used cross-validation and ROC-AUC as the main evaluation metrics.
Results
Achieved high accuracy and ROC-AUC scores on the test set.
Random Forest showed the best performance, but results were checked for overfitting
