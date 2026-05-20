# Credit Card Fraud Detection Using Machine Learning

## Project Overview
This project detects fraudulent credit card transactions using Machine Learning algorithms. The system analyzes transaction patterns and predicts whether a transaction is genuine or fraudulent.

## Objective
The main objective of this project is to:
- Detect fraudulent credit card transactions
- Reduce false positives
- Improve transaction security using Machine Learning

## Dataset
The dataset used in this project is the Credit Card Fraud Detection dataset from Kaggle.

### Dataset Features
- Time
- Amount
- V1 to V28 anonymized PCA features
- Class column
    - 0 = Genuine Transaction
    - 1 = Fraudulent Transaction

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Streamlit

## Machine Learning Algorithm Used
- Random Forest Classifier

## Data Preprocessing
- Missing value checking
- Feature scaling using StandardScaler
- Class balancing using SMOTE

## Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score
- ROC Curve

## Project Workflow
1. Load Dataset
2. Data Preprocessing
3. Handle Class Imbalance using SMOTE
4. Train-Test Split
5. Train Machine Learning Models
6. Evaluate Models
7. Fraud Prediction
8. Data Visualization

## Results
Random Forest Classifier achieved high accuracy and performed better in detecting fraudulent transactions.

## How to Run the Project

### Install Required Libraries
```bash
pip install -r requirements.txt