# 🩺 Diabetes Prediction باستخدام Machine Learning

This project focuses on predicting whether a patient has diabetes based on medical attributes using machine learning models.

## 📌 Project Overview

The goal of this project is to build a classification model that can accurately predict diabetes outcomes using the Pima Indians Diabetes dataset.

The workflow includes:
- Data loading and exploration (EDA)
- Data preprocessing
- Feature scaling
- Model training
- Hyperparameter tuning
- Model evaluation

---

## 📊 Dataset

The dataset used is `diabetes.csv`, which contains the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (Target variable)

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Machine Learning Models

The following models are used and compared:

- Support Vector Machine (SVM)
- Random Forest Classifier
- Gradient Boosting Classifier

Hyperparameter tuning is performed using **GridSearchCV**.

---

## 🧠 Workflow

1. Load dataset
2. Perform Exploratory Data Analysis (EDA)
3. Handle missing values (KNN Imputer)
4. Feature scaling (StandardScaler)
5. Split data into training and testing sets
6. Train models
7. Tune hyperparameters
8. Evaluate model performance

---

## 📈 Evaluation Metrics

- Accuracy Score
- Classification Report (Precision, Recall, F1-score)

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction.git
