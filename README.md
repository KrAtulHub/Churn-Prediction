# 🔍 Customer Churn Prediction

This project uses a neural network model to predict customer churn based on subscription and service-related features.

---

## 🖼️ Sample Output / Architecture

"C:\Users\DELL\OneDrive\Pictures\Screenshots\Screenshot 2025-07-13 110516.png"
"C:\Users\DELL\OneDrive\Pictures\Screenshots\Screenshot 2025-07-13 110545.png"

> _Replace the image above with any accuracy/loss plot or model diagram (like a screenshot from your notebook)._

---

## 📈 Accuracy

Achieved over **85% training accuracy** using TensorFlow and Keras on a binary classification problem.

---

## 📊 Input Features

The model uses the following key features:

- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `PhoneService`, `MultipleLines`
- `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`
- `TechSupport`, `StreamingTV`, `StreamingMovies`
- `PaperlessBilling`, `MonthlyCharges`, `TotalCharges`
- One-hot encoded columns for:
  - Internet Service (`DSL`, `Fiber optic`, `No`)
  - Contract Type (`Month-to-month`, `One year`, `Two year`)
  - Payment Method

---



