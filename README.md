# Loan Approval and Maximum Loan Amount Prediction

A machine learning project that predicts loan approval status and maximum
loan amount for bank clients using classification and regression models.

## Project Overview
This project covers two case studies:
- **Case Study A:** Predicting client loan approval status (classification)
- **Case Study B:** Predicting the maximum loan amount for approved clients (regression)

## Repository Structure
├── w2121370_Final_python_notebook_1.ipynb
├── w2121370_Final_python_notebook_2.ipynb
├── w2121370_Final_python_notebook_3.ipynb
├── loan_approval_data.csv
├── Classification_Loan_Data.csv
├── Regression_Loan_Data.csv
└── README.md

└── README.md

## Models Used
- Logistic Regression
- K-Nearest Neighbours (KNN) with GridSearchCV tuning
- Naïve Bayes
- Soft Voting Ensemble Classifier (LR + NB)
- Decision Tree Regressor (fully grown and pruned)

## Key Results
| Model | F1-Score (Reject class) | AUC-ROC |
|---|---|---|
| Logistic Regression | 0.35 | 0.84 |
| KNN (k=5) | 0.48 | 0.81 |
| KNN Tuned (k=9, manhattan) | 0.51 | 0.84 |
| Naïve Bayes | 0.44 | 0.81 |
| Ensemble (LR + NB) | 0.43 | 0.83 |

Regression (Maximum Loan Amount):
| Model | MSE | R² |
|---|---|---|
| DT-1 Fully Grown | 447,895,126 | 0.85 |
| DT-2 Pruned (depth=4) | 829,592,976 | 0.73 |

## Tech Stack
- Python 3
- Pandas, NumPy
- Scikit-learn
- Plotly Express
- Matplotlib

## How to Run
1. Clone the repository
2. Upload the notebooks to Google Colab or run locally with Jupyter
3. Ensure the CSV files are in the same directory as the notebooks
4. Run notebooks in order: Notebook 1 → 2 → 3
