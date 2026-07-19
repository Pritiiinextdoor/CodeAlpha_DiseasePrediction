# CodeAlpha_DiseasePrediction

## Objective
Predict the possibility of disease (diabetes) based on patient data, as part of the CodeAlpha Machine Learning Internship (Task 4).

## Dataset
Pima Indians Diabetes Dataset (UCI ML Repository) — 768 records, 8 medical features (Glucose, BMI, Age, Blood Pressure, etc.), target variable: Outcome (0 = No Diabetes, 1 = Diabetes).

## Approach
- Handled invalid/missing values (0s replaced with median)
- Feature scaling using StandardScaler
- Trained Logistic Regression, Random Forest, and SVM models
- Evaluated using Accuracy, Precision, Recall, Confusion Matrix, ROC-AUC

## Results
- Logistic Regression Accuracy: [fill in]
- Random Forest Accuracy: [fill in]
- SVM Accuracy: [fill in]
- ROC-AUC Score (Random Forest): 0.834
