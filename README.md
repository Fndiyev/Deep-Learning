<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=50&duration=4000&pause=1000&color=FFFFFF&background=000000&center=true&vCenter=true&width=800&height=100&lines=DEEP-LEARNING" alt="Deep-Learning" />
  
  <div style="margin: 20px 0;">
    <img src="https://img.shields.io/github/stars/Fndiyev/Deep-Learning?style=for-the-badge&logo=github&logoColor=white&color=black&labelColor=black" alt="GitHub stars"/>
    <img src="https://img.shields.io/github/forks/Fndiyev/Deep-Learning?style=for-the-badge&logo=github&logoColor=white&color=black&labelColor=black" alt="GitHub forks"/>
    <img src="https://img.shields.io/github/issues/Fndiyev/Deep-Learning?style=for-the-badge&logo=github&logoColor=white&color=black&labelColor=black" alt="GitHub issues"/>
    <img src="https://img.shields.io/github/license/Fndiyev/Deep-Learning?style=for-the-badge&logo=github&logoColor=white&color=black&labelColor=black" alt="GitHub license"/>
  </div>
  
# Heart Disease Prediction Using Deep Learning 🫀

This project implements a deep learning model to predict the presence of heart disease based on clinical parameters. The goal is to demonstrate how neural networks can assist in early diagnosis using structured medical data.

## 🎯 Objective

To build a binary classification model using deep learning techniques that can predict whether a person has heart disease based on various health indicators.

## 📌 Dataset

- Source: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease) or similar public dataset.
- Features include:
  - Age
  - Sex
  - Chest Pain Type
  - Resting Blood Pressure
  - Cholesterol
  - Fasting Blood Sugar
  - Resting ECG
  - Max Heart Rate
  - Exercise-Induced Angina
  - Oldpeak (ST depression)
  - Slope, CA, Thal
  - Target (1: disease, 0: no disease)

## 🛠️ Tools & Libraries

- Python 3
- NumPy & Pandas
- scikit-learn
- TensorFlow / Keras
- Matplotlib / Seaborn (for visualizations)

## ⚙️ Workflow

1. Data Preprocessing
   - Handle missing values
   - Encode categorical features
   - Normalize numeric features
2. Model Building
   - Deep Neural Network using Keras Sequential API
3. Evaluation
   - Accuracy, Confusion Matrix, Precision/Recall
4. Prediction on test data

## 📊 Output

The model prints evaluation metrics and plots loss/accuracy curves over epochs. It may also support user input for real-time predictions.
