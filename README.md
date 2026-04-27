# Customer-Churn-Prediction

A full-stack data analytics application that predicts customer churn using machine learning and presents actionable insights through an interactive web dashboard.

This system integrates a Flask web application, machine learning models, SQL database, and an automated data pipeline to analyze customer behavior and identify customers at risk of leaving.

Project Overview

Customer churn is a critical issue for businesses, directly impacting revenue and growth. This project focuses on analyzing customer data to predict churn and support proactive decision-making.

The application automates the complete workflow—from data processing and prediction to storage and visualization—within a unified platform.

Key capabilities:

Predict customer churn with probability scores
Identify high-risk customers
Estimate potential revenue loss
Visualize churn trends and patterns
Perform reason-based churn analysis
Features
Machine learning-based churn prediction
Automated data processing and prediction pipeline
Interactive analytics dashboard
Churn distribution and trend visualization
Revenue loss estimation
Contract-based churn analysis
Reason analysis for churn behavior
Secure login and authentication system
SQL database integration for data management
Tech Stack
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
SQLAlchemy
Visualization
Plotly
Frontend
HTML
CSS
Bootstrap
JavaScript
Project Structure
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
Installation
1. Clone the Repository
git clone https://github.com/your-username/customer-churn-dashboard.git
2. Navigate to Project Folder
cd customer-churn-dashboard
3. Install Dependencies
pip install -r requirements.txt
Running the Application

Start the Flask server:

python app.py

Open your browser and navigate to:

http://127.0.0.1:5000

Login to access the dashboard and explore churn insights.

Machine Learning Pipeline

The system follows a structured pipeline:

Fetch customer data from the database
Perform data cleaning and preprocessing
Load the trained churn prediction model
Predict churn probability for each customer
Store results in the database
Display insights through the dashboard
Dashboard Analytics

The dashboard provides key business insights, including:

Total number of customers
Predicted churn count
Churn rate (%)
Revenue loss estimation
Churn distribution visualization
Contract-wise churn analysis
Reason-based churn insights

These insights enable organizations to understand customer behavior and implement effective retention strategies.

Future Enhancements
Real-time churn prediction system
Integration of advanced ML models (XGBoost, LightGBM)
Customer segmentation analysis
Automated alerts for high-risk customers
Cloud deployment for scalability
Role-based authentication and access control
