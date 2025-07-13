# 🔍 Customer Churn Prediction

This project uses a neural network model to predict customer churn based on subscription and service-related features.

---

## 🖼️ Sample Output / Architecture

(![Screenshot 2025-06-18 060800](https://github.com/user-attachments/assets/8fd69f69-7fc7-4b83-983e-1655ae9d0c4a)
)

> _The images above show the model's confusion matrix and training accuracy over epochs. Replace the URLs with your actual uploaded GitHub-hosted image links._

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

## 🛠 How to Add Images to GitHub README Without Uploading to Repo

1. Go to your GitHub repository → **Issues** → **New Issue**
2. Drag and drop your screenshot(s) into the comment box
3. GitHub will upload them and give you direct image links like:





