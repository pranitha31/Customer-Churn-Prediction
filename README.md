# Customer-Churn-Prediction

🚀 Customer Churn Prediction & Analytics Dashboard


A full-stack data analytics application that predicts customer churn using machine learning and presents actionable insights through an interactive web dashboard.


This system integrates a Flask web application, machine learning models, SQL database, and an automated data pipeline to analyze customer behavior and identify customers at risk of leaving.


📌 Project Overview


Customer churn is a critical issue for businesses, directly impacting revenue and growth. This project focuses on analyzing customer data to predict churn and support proactive decision-making.


The application automates the complete workflow—from data processing and prediction to storage and visualization—within a unified platform.


🔑 Key Capabilities
Predict customer churn with probability scores
Identify high-risk customers
Estimate potential revenue loss
Visualize churn trends and patterns
Perform reason-based churn analysis


✨ Features
Machine learning-based churn prediction
Automated data processing and prediction pipeline
Interactive analytics dashboard
Churn distribution and trend visualization
Revenue loss estimation
Contract-based churn analysis
Reason analysis for churn behavior
Secure login and authentication system
SQL database integration for data management


🛠️ Tech Stack

Backend
Python
Flask

Machine Learning
Scikit-learn
Data Processing
Pandas
NumPy

Database
SQLite

Visualization
Plotly

Frontend
HTML
CSS

JavaScript
📁 Project Structure
customer-churn-dashboard
│
├── app.py
├── pipeline.py
├── config.py
├── step2_predict_churn.py
├── requirements.txt
│
├── CustomerChunSystem
│   ├── __init__.py
│   └── fetch_data.py
│
├── templates
│   ├── login.html
│   └── dashboard.html
│
├── static
│   ├── css
│   │   └── style.css
│   └── js
│       └── scripts.js
│
├── models
│   └── churn_model.pkl
│
├── database
│   └── churn_database.db
│
└── data
    ├── raw
    ├── processed
    └── predictions
