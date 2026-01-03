# Credit Card Fraud Detection

## Problem Statement
Credit card fraud is a major issue in the financial industry, causing significant
financial losses every year. Detecting fraudulent transactions accurately and in
real time is challenging due to highly imbalanced data and evolving fraud patterns.
This project aims to identify fraudulent credit card transactions using machine
learning techniques.

## Objective
The objective of this project is to build a machine learning model that can
classify credit card transactions as fraudulent or legitimate based on transaction
features.

## Dataset
- Source: Kaggle Credit Card Fraud Dataset
- Description: The dataset contains credit card transactions made by European
  cardholders. It includes numerical features resulting from PCA transformation,
  along with Time, Amount, and Class (fraud or non-fraud).
- Class Distribution: Highly imbalanced (fraud cases < 1%)

## Tech Stack
- Programming Language: Python
- Libraries:
  - NumPy
  - Pandas
  - Matplotlib / Seaborn
  - Scikit-learn
- Tools: Jupyter Notebook

## Methodology
1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Handling class imbalance (undersampling / oversampling / SMOTE)
4. Feature scaling
5. Model training
6. Model evaluation and comparison

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- (Optional) XGBoost

## Evaluation Metrics
Since the dataset is imbalanced, the following metrics are used:
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

## Results
- The Random Forest model achieved the best performance with high recall and
  ROC-AUC score.
- The model effectively detects fraudulent transactions while minimizing
  false negatives.

(Mention exact metric values if available)

## Conclusion
This project demonstrates the application of machine learning techniques to
detect fraudulent credit card transactions. Proper handling of class imbalance
and the use of appropriate evaluation metrics significantly improve fraud
detection performance.

## Future Enhancements
- Use advanced ensemble methods like XGBoost or LightGBM
- Implement real-time fraud detection
- Deploy the model using Flask or FastAPI
- Integrate with a live transaction stream

## How to Run the Project
1. Clone the repository
2. Install dependencies: 
