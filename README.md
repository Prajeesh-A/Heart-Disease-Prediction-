# Heart Disease Prediction using Gradio

## Overview
This project provides a machine learning-based web application for predicting heart disease using a trained Random Forest model. The application is built using **Gradio** for an interactive user interface and can be run on **Google Colab**.

## Features
- Interactive web UI for heart disease prediction
- Uses a **Random Forest model** trained on medical data
- **Gradio** for easy access and testing
- **Scikit-learn StandardScaler** for input normalization

## Prerequisites
To run this project, you need the following:
- Google Colab (or a local Python environment)
- Python 3.x
- Required Python libraries:
  ```bash
  pip install gradio numpy scikit-learn pickle-mixin
  ```

## Files
- `random_forest_model.pkl`: Pre-trained Random Forest model
- `scaler.pkl`: StandardScaler for input normalization
- `AI_Heart_disease.ipynb`: Jupyter Notebook for model training and deployment
- `heart_disease_gradio.py`: Gradio-based app script

## How to Run
1. Upload `random_forest_model.pkl` and `scaler.pkl` to your Colab workspace.
2. Copy and run the `heart_disease_gradio.py` script.
3. Click on the Gradio-generated link to access the web interface.
4. Enter the patient details and get a prediction.

## Input Parameters
- **Age**: Patient's age (0-120)
- **Sex**: Male (M) or Female (F)
- **Chest Pain Type**: [ATA, NAP, ASY, TA]
- **Resting Blood Pressure**: 0-200
- **Cholesterol**: 0-500
- **Fasting Blood Sugar**: 0 or 1
- **Resting ECG**: [Normal, ST, LVH]
- **Max Heart Rate Achieved**: 60-220
- **Exercise Angina**: Yes (Y) or No (N)
- **Oldpeak**: 0.0-6.0
- **ST Slope**: [Up, Flat, Down]

## Output
- **Heart Disease Detected**: If the model predicts the presence of heart disease.
- **No Heart Disease**: If the model predicts no heart disease.

## License
This project is for educational purposes and is open-source.

## Author
Developed by Prajeesh

