# Credit Risk Classification

## Overview
This project uses a logistic regression model to classify credit risk as either healthy loans (`0`) or high-risk loans (`1`) based on a peer-to-peer lending dataset.

## Results
- **Class 0 (Healthy Loan):**
  - Precision: 1.00
  - Recall: 0.99
  - F1-Score: 1.00
- **Class 1 (High-Risk Loan):**
  - Precision: 0.86
  - Recall: 0.94
  - F1-Score: 0.90
- **Overall Metrics:**
  - Accuracy: 0.99
  - Macro Average Precision: 0.93
  - Macro Average Recall: 0.97
  - Weighted Average F1-Score: 0.99

## Summary
The logistic regression model effectively predicts both healthy and high-risk loans. While it is highly precise and accurate for healthy loans, it demonstrates slightly lower precision for high-risk loans. However, its recall and F1-score for high-risk loans indicate strong performance, making it suitable for deployment in credit risk assessment.

## Repository Structure
- `credit_risk_classification.ipynb`: Jupyter Notebook containing the code and analysis.
- `lending_data.csv`: Dataset used for training and testing.
- `README.md`: This file.

## Tools Used
- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
