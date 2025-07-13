# 🔍 Customer Churn Prediction

This project uses a neural network model to predict customer churn based on subscription and service-related features.

---

## 🖼️ Sample Output / Architecture
<img width="644" height="491" alt="Screenshot 2025-07-13 110516" src="https://github.com/user-attachments/assets/9be9dda2-fd02-4c65-ace9-a34ac5d8504e" />

<img width="725" height="736" alt="Screenshot 2025-07-13 110545" src="https://github.com/user-attachments/assets/9a962944-103d-4ec7-876e-16ded1105317" />


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

## 🛠️ Technologies Used

- **Python** (TensorFlow, Keras, Pandas, scikit-learn, Matplotlib)
- **Jupyter Notebook**
- Cleaned `.csv` dataset 

---

## ✍️ Author

Made by **Atul Kumar Prasad**





