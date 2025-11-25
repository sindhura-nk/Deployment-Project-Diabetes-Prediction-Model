# 📌 Diabetes Prediction Model (Multiclass Classification & Deployment)
🔍 **Project Overview**

This project focuses on building a Multiclass Diabetes Prediction Model and deploying it using Streamlit.

The goal is to classify individuals into different diabetes risk categories based on health-related features using a Machine Learning model.

The project includes:
  Data preprocessing
  
  Exploratory data analysis
  
  Model building (Multiclass Classification)
  
  Model evaluation
  
  Saving and loading the trained model
  
  Creating an interactive Streamlit web application
  
  Deployment on Streamlit Cloud

## 🧠 Model Details
**1. Dataset**

The model uses a diabetes dataset containing several predictive health parameters such as Glucose level, Blood pressure, BMI, Age, Insulin, Skin thickness, Pregnancies, Diabetes pedigree function.

The target column: Outcome, which contains multiple classes (multiclass labels indicating various risk levels).

**2. Data Preprocessing**

You performed the following steps before model training:
  
  Handling missing or zero-value data
  
  Normalizing numerical features
  
  Splitting the dataset into train and test sets
  
  Encoding the multiclass target variable if needed
  
  Feature scaling to improve model performance

**3. Model Training**

You experimented with different classification algorithms and finalized one after evaluating metrics such as:

Accuracy

Classification report

Confusion matrix

The final trained model was saved using pickle and loaded inside the Streamlit app.

## 🌐 Streamlit Application

Your Streamlit app provides a simple and user-friendly interface through which users can:

## ✔ Enter health-related input values

Inputs include:
Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age, 

These are collected through Streamlit number input components.

## ✔ Model Prediction

The input data is processed into the format expected by your model.

The trained model predicts the diabetes class/risk level.

The output is displayed clearly to the user.

## ✔ UI/UX Features

Clean layout built using st.title, st.subheader, and st.number_input.

Real-time prediction when the user clicks the "Predict" button.

Friendly messages showing prediction results.

## 🚀 Deployment

Your complete machine learning project was deployed through Streamlit Cloud.

You pushed all the necessary files (app.py, model file, requirements.txt) to GitHub.

Streamlit Cloud automatically built and deployed the app using your repository.

Users can now access your model online at:

## 🔗 Deployed App:
https://deployment-project-diabetes-prediction-model-sindhura-nk.streamlit.app/

📁 **Repository Structure**
📦 Deployment-Project-Diabetes-Prediction-Model
 ┣ 📜 app.py                # Streamlit application
 ┣ 📜 trained_model.pkl     # Saved machine learning model
 ┣ 📜 scaler.pkl            # Scaler used during preprocessing (if used)
 ┣ 📜 requirements.txt      # Python dependencies
 ┗ 📜 README.md             # Project documentation

## 🛠 Technologies Used

Python

Pandas, NumPy – Data preprocessing

Scikit-learn – Model development

Pickle – Saving trained model

Streamlit – Frontend UI + deployment

GitHub + Streamlit Cloud – Hosting & deployment
