# 🌧️ Rainfall Prediction Classifier

This project focuses on building a machine learning classifier to predict whether it will rain tomorrow based on historical weather data. The model is trained and evaluated using various weather features, leveraging Python's robust data science libraries.

---

## 🚀 Overview

Rainfall prediction is essential for agriculture, disaster management, and water resource planning. This project provides a binary classification model that predicts **"RainTomorrow"** (`Yes` or `No`) using weather parameters such as temperature, humidity, wind speed, and more.

---

## 📊 Model Accuracy

- **Model Used**: Random Forest Classifier  
- **Accuracy Achieved**: **84%** on the test set

---

## 🧰 Tech Stack

- **Programming Language**: Python

- **Libraries**:
  - `Pandas` – Data manipulation and analysis
  - `NumPy` – Numerical computing
  - `Matplotlib`, `Seaborn` – Data visualization
  - `Scikit-learn` – Machine learning (training, testing, evaluation)

- **Model**:
  - `RandomForestClassifier` from `sklearn.ensemble`

---

## 🧪 Features Used

- **Input Features**: `MinTemp`, `MaxTemp`, `Rainfall`, `WindGustSpeed`, `Humidity`, `Pressure`, `Cloud`, etc.
- **Target Variable**: `RainTomorrow` (`Yes` / `No`)

---

## 📈 Performance Metrics

- **Accuracy**: 84%
- **Evaluation Metrics**:
  - Confusion Matrix
  - Classification Report:
    - Precision
    - Recall
    - F1-Score

---

## 📂 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rainfall-prediction-classifier.git
