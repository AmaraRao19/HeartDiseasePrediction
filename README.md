# HeartDiseasePrediction

## Task Objective
Predict whether a patient is at risk of heart failure using Machine Learning.

## Dataset Used
- Dataset: Heart Failure Records Dataset (from Kaggle/UCI)
- Features include: age, sex, ejection_fraction, serum_creatinine, serum_sodium, high_blood_pressure, diabetes, smoking, and others.
- Target variable: `DEATH_EVENT` (1 = patient died, 0 = patient survived)
- Total records: 299 patients

## Model Applied
- Clasification (Logistic Regression)

## Key Results & Findings
- Accuracy: 85%
- Important Features: age, ejection_fraction, serum_creatinine
- Insights: The model predicts patients at higher risk of heart failure based on key clinical parameters. Logistic Regression works well for this binary classification task.

## How to Run
1. Open `HeartDiseasePrediction.ipynb` in Google Colab.
2. Run all cells to train and evaluate the Logistic Regression model.
3. The results, plots, and metrics will display in the notebook.
