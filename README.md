# diabetes-prediction-logistic-regression

# 🩺 Diabetes Prediction Web App - Logistic Regression (ML Project)

This project is a **Machine Learning-based web application** that predicts whether a person is diabetic or not, based on medical diagnostic features. The model is trained using the **Logistic Regression** algorithm and deployed with **Flask** as a user-friendly web interface.



## 🔍 Problem Statement

Early detection of diabetes can help in managing the disease and reducing complications. This web app allows users to input health data such as glucose level, insulin, BMI, age, and receive a prediction whether the individual is likely diabetic.

---

## 💡 Features

- ✅ Trained Logistic Regression Model on PIMA Indian Diabetes Dataset
- ✅ Feature scaling with `StandardScaler`
- ✅ User input via web form (HTML + Flask)
- ✅ Clean UI with prediction display (`Diabetic` / `Non-Diabetic`)
- ✅ Modular code with `app.py`, templates, and models separated
  

---

## 🛠️ Tech Stack

| Component      | Technology           |
|----------------|----------------------|
| ML Algorithm   | Logistic Regression (Scikit-learn) |
| Web Framework  | Flask                |
| Language       | Python               |
| Frontend       | HTML + Jinja2        |
| Preprocessing  | StandardScaler       |
| Dataset        | PIMA Indian Diabetes Dataset |

---

## 🧠 Model Inputs

The model expects the following features:

- `Pregnancies`
- `Glucose`
- `BloodPressure`
- `SkinThickness`
- `Insulin`
- `BMI`
- `DiabetesPedigreeFunction`
- `Age`

## 📈 Conclusion

The Logistic Regression model achieved an accuracy of **73%** on the test set for predicting diabetes. This indicates that the model can correctly classify diabetic vs. non-diabetic 

  

These values are scaled using a fitted `StandardScaler` before prediction.

---


