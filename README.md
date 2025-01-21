# HealthCare_Recommedation_System

# Overview
The Healthcare Recommendation System is a Flask-based web application designed to predict diseases based on user-provided symptoms and deliver personalized recommendations. It offers detailed disease descriptions, precautions to be taken, and recommended medications to aid in treatment. Additionally, it provides tailored diet plans and customized workout routines to promote overall health and recovery. This comprehensive approach ensures users receive accurate predictions and actionable advice to manage their health effectively.

# Features

Symptom-Based Disease Prediction:

--> Input symptoms to receive the most probable disease prediction using a trained machine learning model.

Comprehensive Recommendations:

--> Get a detailed description of the disease.

--> Learn precautions to prevent worsening.

--> Access suggested medications, diets, and workout plans.

User-Friendly Interface:

--> Easy-to-navigate Flask web app with additional sections like "About," "Contact," and "Blog."

# Technical Details

Machine Learning Model: Trained Support Vector Classifier (SVC).

Key Components:

--> Datasets: Symptoms, precautions, workout plans, descriptions, medications, and diets.

--> Libraries: Flask, NumPy, Pandas, Pickle.

Prediction Mechanism:

--> Converts user input into a binary vector.

--> Predicts disease using the SVC model.

--> Fetches recommendations from corresponding datasets.

# How It Works

Enter symptoms (e.g., "itching, skin_rash, fatigue") into the input field.

The system predicts the disease and fetches detailed recommendations.

Outputs include:

The outputs of the system include a detailed disease description, along with essential precautions and recommended medications to address the identified condition. Additionally, it provides tailored diet plans and workout routines to support recovery and promote overall well-being.

# Setup
1.Clone the repository and install dependencies:
```
git clone
 ```
```
pip install -r requirements.txt
 ```

2.Place the datasets in the datasets folder and the model file (svc.pkl) in the models folder.

3.Run the application:
```
python app.py
 ```
