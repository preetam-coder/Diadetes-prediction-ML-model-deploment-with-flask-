Diabetes Prediction ML Model Deployment using Flask

This project demonstrates how to deploy a trained Machine Learning model as an API using Flask in Python.

As a part of my learning, I trained a Logistic Regression model for Diabetes Prediction, saved the model using Pickle, and created API endpoints that accept input data and return prediction results in JSON format.

Features

Logistic Regression based ML model

Data preprocessing & scaling

Model + scaler saved using pickle

Flask API endpoints (/ and /predict)

Input validation & error handling

Returns prediction as JSON response

Tech Stack

Python

Flask

Pandas

Scikit-learn

Pickle

How it works

User sends input values (pregnancies, glucose, blood pressure, etc.)

Data gets scaled using saved scaler

Model makes prediction

API returns “Diabetic / Not Diabetic”

Project Goal

To understand the process of deploying ML models as REST APIs and making them usable outside Jupyter notebooks.
