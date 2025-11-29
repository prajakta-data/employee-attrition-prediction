# Employee Attrition Prediction
## Dataset

The dataset used in this project is from Kaggle:

IBM HR Analytics Employee Attrition Dataset  
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

Due to licensing and size constraints, the dataset is not included in this repository.
Please download it from the above link and place the file inside:

data/WA_Fn-UseC_-HR-Employee-Attrition.csv


This project predicts whether an employee is likely to leave the organization using machine learning techniques.

## Objectives
- Clean and analyze HR data
- Engineer meaningful features
- Train ML models
- Perform hyperparameter tuning
- Evaluate performance
- Extract business insights

## Tools & Libraries
- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn

## Models Used
- Logistic Regression
- Random Forest (Tuned with GridSearchCV)

## Results
- ROC-AUC score: XX (replace with your best score)
- Key predictors:
  - MonthlyIncome
  - Age
  - Job role
  - Total working years
  - Overtime


employee-attrition-prediction/
│
├── notebooks/
├── reports/
├── README.md


## How to Run
1. Clone the repository
2. Open `01_employee_attrition_prediction.ipynb`
3. Run all cells

## Project Structure
employee-attrition-prediction/
│
├── notebooks/
├── reports/
├── README.md
