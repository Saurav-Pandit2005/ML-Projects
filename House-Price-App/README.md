# 🏠 House Price Prediction App

A Machine Learning powered web application that predicts house prices based on various housing features.

## 🚀 Live Demo
🔗 Streamlit App: https://house-price-predictor-saurav.streamlit.app/

## 📌 Project Overview

This project uses a Machine Learning Regression model to estimate house prices using real housing data.  
The application is built with:

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy

The trained model is deployed on Streamlit Cloud for interactive predictions.

---

## ⚙️ Features Used

The model predicts house prices based on:

- 📐 Living Area
- 🛏 Bedrooms
- 🛁 Bathrooms
- 🚗 Garage Area
- ⭐ Overall Quality
- 🏗 Year Built
- 🧱 Basement Area

---

## 🧠 Machine Learning Model

- Algorithm Used: **Random Forest Regressor**
- Evaluation Metric: **R² Score**
- Achieved Accuracy: **0.87 R² Score**

---

## 📂 Project Structure

```bash
House-Price-App/
│
├── app/
│   ├── app.py
│   └── requirements.txt
│
├── data/
│   └── train.csv
│
├── model/
│   └── model.pkl
│
├── notebook/
│   └── model.py
