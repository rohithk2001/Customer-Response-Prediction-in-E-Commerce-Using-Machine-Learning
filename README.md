# Customer-Response-Prediction-in-E-Commerce-Using-Machine-Learning
🧩 Problem Statement (What problem it solved)

E-commerce platforms generate highly imbalanced customer data, where a small group of customers contributes to most purchases. Traditional machine-learning models tend to be biased toward non-purchasing customers, leading to poor prediction of high-value users and ineffective targeted marketing.

This project addresses:

Class imbalance in customer response data

Low accuracy and instability of single decision-tree models

Lack of behavioral insight in prediction models

🛠️ Technologies & Techniques Used (What we used)

Machine Learning Algorithms

Decision Tree Classifier

Random Forest (Bagging)

XGBoost (Boosting)

Data Preprocessing

SMOTE (Synthetic Minority Over-sampling Technique)

Feature engineering using behavioral metrics (RFM)

Evaluation Metrics

Accuracy

Precision, Recall, F1-Score

ROC-AUC

Tools

Python

Scikit-learn

XGBoost

Pandas, NumPy

⚙️ Implementation Approach (How it was implemented)

Preprocessed raw e-commerce customer data and identified class imbalance between purchasing and non-purchasing users

Applied SMOTE to synthetically balance minority class samples and reduce model bias

Engineered customer behavioral features including purchase recency, frequency, and monetary value (RFM analysis)

Trained and evaluated:

A baseline Decision Tree model

Random Forest to reduce variance using bagging

XGBoost to improve prediction through boosting

Compared model performance on balanced vs unbalanced datasets using standard classification metrics

Demonstrated that ensemble models combined with balanced data and behavioral features significantly improved predictive accuracy and generalization

📈 Key Outcome / Impact

Improved prediction of high-value customers in imbalanced e-commerce datasets

Reduced majority-class bias in customer response forecasting

Enabled more accurate and reliable targeted marketing strategies
