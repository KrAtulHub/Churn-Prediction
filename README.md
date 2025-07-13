# 🔍 Customer Churn Prediction

This project uses a neural network model to predict customer churn based on subscription and service-related features.

---

## 🖼️ Sample Output / Architecture

![Model Output](images/output_plot.png)

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



