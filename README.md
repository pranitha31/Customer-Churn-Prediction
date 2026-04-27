# Customer Churn Prediction & Analytics Dashboard

A full-stack data analytics project that predicts customer churn using machine learning and presents insights through an interactive web dashboard.

The system integrates a **Flask web application, machine learning model, SQL database, and automated data pipeline** to analyze customer behavior and identify customers at risk of leaving.

---

## 📌 Project Overview

Customer churn is a critical challenge for businesses, directly impacting revenue and growth. This project focuses on analyzing customer data and predicting churn using machine learning techniques.

The application automatically runs a prediction pipeline, stores results in a database, and visualizes insights through an intuitive dashboard.

---

## 🚀 Key Capabilities

- Predict customer churn  
- Identify high-risk customers  
- Estimate potential revenue loss  
- Visualize churn trends and patterns  
- Perform reason-based churn analysis  

---

## ✨ Features

- Machine Learning-based churn prediction  
- Automated ML pipeline execution  
- Interactive analytics dashboard  
- Customer churn distribution visualization  
- Revenue loss estimation  
- Churn analysis by contract type  
- Reason-based churn insights  
- Secure login system  
- SQL database integration  

---

## 🛠️ Tech Stack

### Backend
- Python  
- Flask  

### Machine Learning
- Scikit-learn  

### Data Processing
- Pandas  
- NumPy  

### Database
- SQLite  
- SQLAlchemy  

### Visualization
- Plotly  

### Frontend
- HTML  
- CSS  
- Bootstrap  
- JavaScript  

---

## 📂 Project Structure

```text
customer-churn-dashboard/
│
├── app.py
├── pipeline.py
├── config.py
├── step2_predict_churn.py
├── requirements.txt
│
├── CustomerChunSystem/
│   ├── __init__.py
│   └── fetch_data.py
│
├── templates/
│   ├── login.html
│   └── dashboard.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── scripts.js
│
├── models/
│   └── churn_model.pkl
│
├── database/
│   └── churn_database.db
│
└── data/
    ├── raw/
    ├── processed/
    └── predictions/
