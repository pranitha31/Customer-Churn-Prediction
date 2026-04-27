# Customer Churn Prediction 
A full-stack data analytics project that predicts customer churn using machine learning and displays insights through an interactive web dashboard.

The system combines a **Flask web application, machine learning model, SQL database, and automated data pipeline** to analyze customer behavior and predict which customers are likely to leave a service.

---

## Project Overview

Customer churn is a major challenge for many businesses. This project analyzes customer data and predicts churn using machine learning.

The application automatically runs a prediction pipeline, stores results in a database, and visualizes insights in a dashboard.

### Key Capabilities

- Predicting customer churn  
- Identifying high-risk customers  
- Estimating potential revenue loss  
- Visualizing churn trends and patterns  
- Performing reason-based churn analysis  

---

## Features

- Machine Learning churn prediction  
- Automated ML pipeline execution  
- Interactive analytics dashboard  
- Customer churn distribution visualization  
- Revenue loss estimation  
- Churn analysis by contract type  
- Reason analysis for churn  
- Secure login system  
- SQL database integration  

---

## Tech Stack

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

## Project Structure
customer-churn-dashboard
│
├── app.py
├── pipeline.py
├── config.py
├── step2_predict_churn.py
├── requirements.txt
│
├── CustomerChunSystem
│ ├── init.py
│ └── fetch_data.py
│
├── templates
│ ├── login.html
│ └── dashboard.html
│
├── static
│ ├── css
│ │ └── style.css
│ └── js
│ └── scripts.js
│
├── models
│ └── churn_model.pkl
│
├── database
│ └── churn_database.db
│
└── data
├── raw
├── processed
└── predictions

---

## Installation

### 1. Clone the repository
git clone https://github.com/your-username/customer-churn-dashboard.git

### 2. Navigate to the project folder
cd customer-churn-dashboard
