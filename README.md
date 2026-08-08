# Diabetes Dataset Multiple Regression Analysis

This project applies **Multiple Linear Regression** to two diabetes datasets:
- **UCI Diabetes dataset** (`uci_diabetes.csv`)
- **Pima Indians Diabetes dataset** (`pmi_diabetes.csv`)

## 📌 Features
- Load datasets using **Pandas**
- Select relevant features:
  - Glucose
  - BloodPressure
  - Age
- Target variable:
  - BMI
- Perform multiple regression analysis:
  - Train/test split (80/20)
  - Fit regression model
  - Predict BMI values
  - Evaluate model performance using R² score

## 🚀 Usage
1. Place `uci_diabetes.csv` and `pmi_diabetes.csv` in the project directory.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
