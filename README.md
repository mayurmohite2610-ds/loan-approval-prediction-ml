# Loan Approval Prediction Using Machine Learning

A machine learning classification project that predicts whether a loan application will be approved or rejected based on applicant financial, credit, employment, and asset-related information.

## Dataset

The dataset contains 4,269 loan application records.

Target variable:

- `loan_status` — Approved or Rejected

Important features include:

- Number of dependents
- Education
- Self-employment status
- Annual income
- Loan amount
- Loan term
- CIBIL score
- Residential, commercial, luxury, and bank asset values

## Machine Learning Algorithms Used

- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression

## Project Workflow

1. Loaded and cleaned the dataset
2. Removed extra spaces from column names and values
3. Converted categorical values into numerical values
4. Selected input features and loan status target
5. Split the data into training and testing sets
6. Trained three classification models
7. Evaluated model accuracy and confusion matrices
8. Predicted loan approval for a new applicant

## Libraries Used

- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run

```bash
pip install pandas matplotlib seaborn scikit-learn
python -m notebook
