# AQI Predictor

This repository contains an end-to-end **Air Quality Index (AQI) prediction system**.  
It includes **data preprocessing**, **model training**, **evaluation**, and **Streamlit applications** for different model categories.

---

## 🚀 Quick Start

```bash
git clone <your-repository-link>
cd Aqi_predictor
pip install -r requirements.txt


Run Streamlit Apps
Classical ML Model App
streamlit run classical_models/streamlit_app.py

Neural Network Model App
streamlit run DL_Models/streamlit_app.py

Experimental Model App
streamlit run Experiment/streamlit_app.py


📊 Models
Classical Machine Learning

RandomForestRegressor

SGDRegressor

Gradient Boosting and other baseline models

These offer fast training and reliable performance with minimal preprocessing.

Minimal Feature Regression

A simple AQI regression model using only PM2.5 and PM10, designed for quick estimation.

Neural Networks

Small neural networks built using TensorFlow/Keras, with architectures ranging from 91 to 187 parameters.

Trained on features:

PM2.5

PM10

NO₂

CO

SO₂

O₃

📚 Dataset

Source: Indian Air Pollution Data (2015–2020)

Preprocessing Steps

Missing value handling

Outlier correction

Feature scaling & normalization

Minimal & extended feature selection

🖥️ Streamlit Applications

Each model category includes a dedicated Streamlit UI.
Users can input pollutant values and get AQI predictions powered by different models.

✅ Summary

Multiple AQI prediction models implemented

Includes Classical ML, Minimal models, and Neural Networks

Modular folder structure

Ready-to-use Streamlit applications

Clean, production-ready project setup