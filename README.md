# AQI Predictor

An end-to-end **Air Quality Index (AQI) Prediction** project featuring multiple machine learning and deep learning models with interactive **Streamlit** applications for real-time predictions.

## Features

- Classical Machine Learning models
- Minimal-feature AQI prediction (PM2.5 & PM10)
- Deep Learning models built with TensorFlow/Keras
- Interactive Streamlit dashboards
- Clean and modular project structure

## Installation

```bash
git clone <repository-link>
cd Aqi_predictor
pip install -r requirements.txt
```

## Run the Applications

**Classical ML**
```bash
streamlit run classical_models/streamlit_app.py
```

**Deep Learning**
```bash
streamlit run DL_Models/streamlit_app.py
```

**Experimental Models**
```bash
streamlit run Experiment/streamlit_app.py
```

## Models

- Random Forest Regressor
- SGD Regressor
- Gradient Boosting Regressor
- Minimal Feature Regression (PM2.5 & PM10)
- TensorFlow/Keras Neural Networks

## Dataset

**Source:** Indian Air Pollution Dataset (2015–2020)

**Preprocessing**
- Missing value handling
- Outlier treatment
- Feature scaling
- Feature selection

## Tech Stack

- Python
- Scikit-learn
- TensorFlow/Keras
- Pandas & NumPy
- Streamlit

## Project Structure

```
Aqi_predictor/
├── classical_models/
├── DL_Models/
├── Experiment/
├── requirements.txt
└── README.md
```

## Result

A modular, production-ready AQI prediction system supporting multiple ML/DL approaches through easy-to-use Streamlit interfaces.
