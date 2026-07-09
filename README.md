# Machine Learning Prediction Web Application

## Overview

This project is an interactive Machine Learning web application developed using **Python**, **Scikit-learn**, and **Streamlit**. It allows users to make real-time predictions through a simple and user-friendly interface.

The application demonstrates end-to-end machine learning development, including data preprocessing, model training, hyperparameter tuning, evaluation, and deployment.

---

## Applications Included

### 🏠 House Price Prediction
Predict house prices based on property features using a trained Machine Learning regression model.

### ❤️ Heart Disease Prediction
Predict whether a patient is at risk of heart disease using health-related attributes.

### 💰 Insurance Cost Prediction
Estimate medical insurance charges using demographic and health information.

### 📩 SMS Spam Detection
Detect whether an SMS message is **Spam** or **Not Spam** using TF-IDF vectorization and a Machine Learning classifier.

---

## Features

- Interactive Streamlit dashboard
- Real-time predictions
- User-friendly interface
- Machine Learning model integration
- Data preprocessing
- Model evaluation
- Clean and responsive design

---

## Technologies Used

- Python
- Streamlit
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Matplotlib
- Pickle / Joblib

---

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Data Preprocessing
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Hyperparameter Tuning
8. Model Evaluation
9. Model Deployment using Streamlit

---

## Algorithms Used

### Regression

- Ridge
- Random Forest Regressor
- XGBoost Regressor

### Classification

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

---

## Performance

### House Price Prediction
model:Ridge
- R² Score:81.723

model:Random Forest Regression
- R² Score:91.315

model:XGBoost
- R² Score:92.113

### Heart Disease Prediction

model:Logistic Regression
- Accuracy Score:86.14

model:Random Forest Classifier
- Accuracy Score:88.04

model:XGBoost Classifier
- Accuracy Score:88.04
### Insurance Prediction

model:Ridge
- R² Score:84.406

model:Random Forest Regression
- R² Score:86.079

model:XGBoost
- R² Score:86.482
### SMS Spam Detection

model:Logistic Regression
- Accuracy Score:99.19

model:Random Forest Classifier
- Accuracy Score:98.83

model:XGBoost Classifier
- Accuracy Score:97.67


---

## Project Structure

```
Machine-Learning-Web-App/
│
├── design.py
├── requirements.txt
├── README.md
├── models/
│   ├── house_model.pkl
│   ├── insurance_model.pkl
│   ├── heart_model.pkl
│   └── spam_model.pkl
│
├── datasets/
│
├── images/
│
└── screenshots/
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/romil2019/new_predicted-app.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run design.py
```

---

## Live Demo

Streamlit App:

link :-  https://romil-kumar-ml-app.streamlit.app/

---

## Screenshots

### Home Page


### House Price Prediction

(Add screenshot)

### Heart Disease Prediction

(Add screenshot)

### Insurance Prediction

(Add screenshot)

### SMS Spam Detection

(Add screenshot)

---

## Future Improvements

- AI Chatbot Integration
- AI Automation
- REST API Deployment
- Docker Support
- Cloud Deployment

---

## Author

Romil Kumar

M.Tech in Computer Science and Engineering

Bachelor's Degree in Information Technology
