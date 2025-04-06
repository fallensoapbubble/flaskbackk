# Flask Demand Prediction API

This repository contains a Flask-based web API for demand prediction using machine learning. The application processes demand data, trains a Random Forest Regressor model, and provides an endpoint for making demand predictions based on input features.

---

## Features

- **Preprocessing**: Handles data preprocessing, including date conversion and categorical encoding.
- **Machine Learning**: Utilizes a Random Forest Regressor for demand prediction.
- **Endpoints**:
  - `/` - Welcome message.
  - `/predict_demand` (POST) - Predicts demand based on provided input features.

---

## Requirements

Install the required Python packages using pip:

```bash
pip install flask flask-cors pandas scikit-learn
