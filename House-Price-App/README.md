# House Price Prediction App

A machine learning-powered web application that predicts house prices based on key residential property features.

<a href="https://house-price-predictor-saurav.streamlit.app/">
  <img src="https://img.shields.io/badge/Live-Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
</a>

## Project Overview

The **House Price Prediction App** is a regression-based machine learning application that estimates residential property prices using historical housing data.

The trained model is integrated with a Streamlit web interface, allowing users to enter property details and receive real-time price predictions.

### Built With

* Python
* Streamlit
* Scikit-learn
* Pandas
* NumPy
* Joblib

## Features

The application uses the following property features to generate predictions:

* Living Area
* Number of Bedrooms
* Number of Bathrooms
* Garage Area
* Overall Quality
* Year Built
* Basement Area

## Machine Learning Model

### Algorithm

**Random Forest Regressor**

Random Forest was selected because it can effectively capture non-linear relationships between different housing features and property prices.

### Evaluation Metric

**R² Score**

### Model Performance

**R² Score: 0.87**

The model achieved an R² score of **0.87**, indicating that it explains approximately 87% of the variance in the target house prices on the evaluation data.

## Application Preview

### Main Application Interface

![House Price Prediction App](images/output.png)

> Make sure the screenshot is stored at `images/output.png`. If your screenshot has a different filename, update the image path accordingly.

## Project Structure

```text
House-Price-App/
│
├── app/
│   ├── app.py
│   └── requirements.txt
│
├── data/
│   └── train.csv
│
├── images/
│   └── output.png
│
├── model/
│   └── model.pkl
│
├── notebook/
│   └── model.py
│
└── README.md
```

## Getting Started

Follow the steps below to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Saurav-Pandit2005/ML-Projects.git
```

### 2. Navigate to the Project

```bash
cd ML-Projects/House-Price-App
```

### 3. Install Dependencies

```bash
pip install -r app/requirements.txt
```

### 4. Run the Application

```bash
streamlit run app/app.py
```

The application will start locally and can be accessed through the URL provided by Streamlit.

## Deployment

The application is deployed using **Streamlit Cloud** and is available for real-time predictions through the live demo.

## Key Learning Outcomes

Through this project, I worked with:

* Regression-based machine learning
* Data preprocessing and feature selection
* Random Forest regression
* Model evaluation using R² Score
* Model serialization using Joblib
* Building interactive ML applications with Streamlit
* Deploying machine learning applications to the cloud

## Future Improvements

* Add additional housing features for improved prediction accuracy
* Compare multiple regression algorithms
* Add data visualization and exploratory analysis
* Improve model performance through hyperparameter tuning
* Add prediction confidence or price range
* Improve the user interface and prediction experience

## Author

**Saurav Pandit**

* GitHub: [Saurav-Pandit2005](https://github.com/Saurav-Pandit2005)
* Portfolio: [saurav-portfolio-eosin.vercel.app](https://saurav-portfolio-eosin.vercel.app)

---

If you find this project useful, feel free to explore the repository and the live application.
