# HealthCare_Recommedation_System

# Overview
The Healthcare Recommendation System is a Flask-based web application that predicts diseases based on user-provided symptoms and offers tailored recommendations, including:

1.Disease descriptions

2.Precautions to be taken

3.Recommended medications

4.Suggested diet plans

5.Customized workout plans

# Features

Symptom-Based Disease Prediction:

Input symptoms to receive the most probable disease prediction using a trained machine learning model.

Comprehensive Recommendations:

Get a detailed description of the disease.

Learn precautions to prevent worsening.

Access suggested medications, diets, and workout plans.

User-Friendly Interface:

Easy-to-navigate Flask web app with additional sections like "About," "Contact," and "Blog."

# Technical Details

Machine Learning Model: Trained Support Vector Classifier (SVC).

Key Components:

Datasets: Symptoms, precautions, workout plans, descriptions, medications, and diets.

Libraries: Flask, NumPy, Pandas, Pickle.

Prediction Mechanism:

Converts user input into a binary vector.

Predicts disease using the SVC model.

Fetches recommendations from corresponding datasets.

# How It Works

Enter symptoms (e.g., "itching, skin_rash, fatigue") into the input field.

The system predicts the disease and fetches detailed recommendations.

Outputs include:

Disease description

Precautions

Medications

Diet plans

Workout plans

# Setup
1.Clone the repository and install dependencies:

->git clone <repository-url>

->pip install -r requirements.txt

2.Place the datasets in the datasets folder and the model file (svc.pkl) in the models folder.

3.Run the application:

->python app.py
