# Devices-Price-Classification-System-using-Python-and-Spring-Boot-
This project aims to classify device prices based on their specifications using machine learning. It consists of two main components: a Python project for training the machine learning model and a Spring Boot project for the backend API.

Python Project
# Dataset
The dataset contains specifications of various devices, such as battery power, Bluetooth availability, camera megapixels, etc.
 Training Dataset: https://docs.google.com/spreadsheets/d/1C5K210JMYklz-_naYRaoxXPF6nZIGbXYrn0o0rBeY9I/edit#gid=1607079722
 Test Dataset: https://docs.google.com/spreadsheets/d/1ChyuXQFc7ivtDxdEnbII2lRT3xc6OaMSZp_ud7arf9U/edit#gid=2082460844
# Modeling Steps
Data Preparation:
Clean and preprocess the dataset.
Split the dataset into training and testing sets.
Model Training:
Train a machine learning model (e.g., Random Forest) on the training dataset.
Model Evaluation:
Evaluate the model using accuracy metrics (training accuracy: 97%, test accuracy: 99%).
# Usage
Run the Python script to train the model and save it as model.pkl.
# Spring Boot Project
Entities
Device entity to describe device specifications and predicted price.
Endpoints
GET /api/devices: Retrieve a list of all devices.
GET /api/devices/{id}: Retrieve details of a specific device by ID.
POST /api/devices: Add a new device.
POST /api/predict/{deviceId}: Predict the price for a device and save the result.
# Setup
Configure the application properties to connect to a database.
# Testing
Perform predictions for 10 devices from the test dataset.
 # Documentation
Provide clear documentation on running the application and interacting with the API.
# Future Enhancements
Include more sophisticated machine learning algorithms for better price classification.
Implement user authentication and authorization for API access.
# Technologies Used
Python
Spring Boot
MySQL 
