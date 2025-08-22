# loan_approval_prediction
This project uses the Loan Approval Prediction Dataset (Kaggle) to build a machine learning model that predicts whether a loan application will be approved.

🔹 Project Overview

Objective: Predict loan approval status based on applicant information.

Dataset: Loan-Approval-Prediction-Dataset (Kaggle).

Challenge: The dataset is imbalanced, requiring careful evaluation beyond accuracy.

🔹 Steps Taken
1. Data Preprocessing

Removed irrelevant columns (e.g., loan_id).

Checked and handled missing values.

Encoded categorical features (education, self_employed, loan_status).

Scaled numerical features for model stability.

2. Model Training

Used Logistic Regression with class_weight='balanced' to address class imbalance.

Split dataset into training and testing sets (80/20 split).

3. Evaluation

Metrics used: Accuracy, Precision, Recall, F1-score.

Plotted Confusion Matrix for visualization of classification results.

🔹 Results

The model achieves balanced performance on precision, recall, and F1-score, making it suitable for imbalanced loan approval data.

Confusion Matrix and classification report highlight the effectiveness of the model.

🔹 Tech Stack

Python

Pandas, NumPy

Scikit-learn

Seaborn, Matplotlib

🔹 How to Run

Clone this repository

Install required libraries

pip install -r requirements.txt


Run the Jupyter Notebook or Python script to train and evaluate the model.
