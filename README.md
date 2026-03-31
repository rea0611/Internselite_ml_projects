# 📊 Customer Churn Prediction System

## 🚀 Overview

This project is an end-to-end Machine Learning system that predicts whether a customer is likely to churn based on service usage and billing details. It includes data analysis, model training, and an interactive user interface built using Gradio.

---

## 🎯 Objective

To develop a predictive model that helps businesses identify customers at risk of leaving, enabling proactive retention strategies.

---

## 🧠 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Gradio (UI)

---

## 📁 Project Files

* `churn_project.ipynb` → Complete pipeline (data processing + model + UI)
* `churn.csv` → Dataset
* `churn_model.pkl` → Trained model

---

## ⚙️ Workflow

1. Data loading and preprocessing
2. Feature selection and encoding
3. Model training (Random Forest)
4. Model evaluation
5. Model saving
6. Interactive UI using Gradio

---

## 📊 Model Details

* Algorithm: Random Forest Classifier
* Accuracy: ~75% – 85%
* Evaluation Metrics:

  * Accuracy Score
  * Confusion Matrix
  * Classification Report

---

## 🎨 User Interface (Gradio)

The project includes an interactive UI where users can:

* Input customer details
* Predict churn in real time
* View confidence score

---

## ▶️ How to Run

### Step 1: Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn gradio
```

### Step 2: Open Notebook

Run:

```bash
churn_project.ipynb
```

### Step 3: Launch UI

Run the Gradio cell:

```python
interface.launch()
```

---

## 💡 Features

* Real-time churn prediction
* Interactive web interface inside notebook
* Visual analysis using graphs
* End-to-end ML pipeline

---

## 📌 Key Insights

* Customers with low tenure are more likely to churn
* Higher monthly charges increase churn probability
* Long-term contracts reduce churn

---

## 🔮 Future Scope

* Add explainable AI (SHAP)
* Deploy on cloud platforms
* Integrate real-time customer data
* Improve model accuracy


## ⭐ Conclusion

This project demonstrates how Machine Learning can be applied to solve real-world business problems by predicting customer behavior and improving decision-making.

---
