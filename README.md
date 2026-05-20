# 📊 Customer Churn Analysis & Prediction App

## 🚀 Live Demo

👉 Try this interactive application here:
**[https://telco-churn-analysis.streamlit.app/](https://telco-churn-analysis.streamlit.app/)**

---

## 📌 Project Overview
This project is a Machine Learning-powered Customer Churn Prediction System built to analyze customer behavior and predict whether a customer is likely to leave a service.
It helps businesses improve customer retention strategies using data-driven insights.

---

## 🎯 Objective
- Predict whether a customer will churn (leave) or stay
- Analyze important factors affecting churn
- Provide an interactive UI for real-time predictions

---

## 🧠 Machine Learning Model
- Algorithm: Logistic Regression
- Framework: Scikit-learn
- Type: Binary Classification (Churn / No Churn)

---

## 🛠️ Tech Stack
- Python 🐍
- Pandas 📊
- NumPy 🔢
- Scikit-learn 🤖
- Matplotlib 📈
- Seaborn 📉
- Streamlit ⚡

---

## 📂 Project Structure

telco-churn/
│
├── run.py # Streamlit app
├── churn_model.joblib # Trained ML model
├── churn_model_training.ipynb
├── requirements.txt
└── screenshots/


---

## 📸 App Screenshots

### 🧾 Input Form
![Input Form](screenshots/01_streamlit_input.png)

### 📊 Prediction Result
![Prediction Result](screenshots/02_streamlit_prediction.png)

### 📉 Churn Analysis (Part 1)
![Chart 1](screenshots/03_churn_distribution_1.png)

### 📉 Churn Analysis (Part 2)
![Chart 2](screenshots/04_churn_distribution_2.png)

---

## ⚙️ How to Run Locally

```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/customer-churn-analysis.git

# Move into project folder
cd customer-churn-analysis

# Create virtual environment
python -m venv venv

# Activate environment
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
streamlit run run.py

--

📈 Key Insights

Customers with shorter tenure are more likely to churn
Higher monthly charges increase churn probability
Contract type strongly affects retention

--

💡 Business Impact

This project helps companies:
Reduce customer loss 📉
Improve retention strategies 📊
Increase revenue 💰
Identify risky customers early ⚠️

--
