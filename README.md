
# 🧠 Support Vector Machine (SVM) – Classification and Regression

This project demonstrates the use of Support Vector Machines (SVM) for solving both classification and regression problems. Implemented using `scikit-learn`, it showcases how SVMs can be applied to real-world datasets with preprocessing, model evaluation, and prediction.

---

## 📌 Overview

### 1. 📈 Regression with SVR
- **Objective**: Predict graduate school admission chances based on academic and test-related features.
- **Dataset**: Graduate Admissions dataset (GRE, TOEFL, CGPA, etc.)
- **Steps**:
  - Feature selection and removal of unnecessary columns
  - Dummy encoding for categorical variables
  - Feature scaling using `StandardScaler`
  - Model training using `SVR` with different kernels:
    - Linear
    - Polynomial
    - RBF (Radial Basis Function)
  - Evaluation metrics:
    - Mean Squared Error (MSE)
    - Root Mean Squared Error (RMSE)
    - Mean Absolute Error (MAE)
    - R² score
  - Hyperparameter tuning using `GridSearchCV`
  - Prediction visualization: scatter plot of actual vs. predicted values
  - Feature importance using permutation importance
  - Simulation of new candidate predictions

---

### 2. ✅ Classification with SVC
- **Objective**: Predict customer churn using categorical and numerical attributes.
- **Dataset**: Telecom churn dataset
- **Steps**:
  - Dummy encoding of categorical variables
  - Scaling of numerical features
  - Model training using `SVC` with various kernels:
    - Linear
    - Polynomial
    - RBF
  - Performance metrics:
    - Accuracy
    - Precision
    - Sensitivity (Recall)
    - Specificity
  - Confusion matrix visualization for train and test sets
  - Hyperparameter optimization via `GridSearchCV`
  - Permutation-based feature importance ranking
  - Prediction of churn for new client data

---

## 🧰 Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Scipy (for permutation importance)

---

