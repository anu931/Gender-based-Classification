# 👥 Gender Classification using Logistic Regression

This project uses machine learning techniques to classify gender based on facial features using a dataset of biometric measurements. The classification model is built using **Logistic Regression** from `scikit-learn`.

---
## 📁 Dataset

The dataset `gender_class.csv` includes 5000 rows and 8 columns, containing the following features:

- `long_hair`
- `forehead_width_cm`
- `forehead_height_cm`
- `nose_wide`
- `nose_long`
- `lips_thin`
- `distance_nose_to_lip_long`
- `gender` (target variable)

---

## 🔍 Objective

To build a classification model that can predict gender (`0` for Female, `1` for Male) based on facial measurements using logistic regression.

---

## 📦 Requirements

Install the required Python libraries:

```bash

pip install numpy pandas matplotlib seaborn scikit-learn

## 📊 **Result & Accuracy**

**This section summarizes the performance of the model including accuracy, confusion matrix, and classification metrics.**

### ✅ Model Accuracy

- **Accuracy:** `87.27%`  
  (calculated using `accuracy_score(y_test, y_pred)`)

### 🧮 Confusion Matrix
---






