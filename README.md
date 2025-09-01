# Predictive_Maintenance_Project
A comprehensive Predictive Maintenance project demonstrating machine learning and deep learning techniques to predict Remaining Useful Life (RUL) of industrial equipment.
# Predictive Maintenance Project

This project showcases a full workflow for **Predictive Maintenance (PdM)** using both classical and deep learning models:

## Features:
- Synthetic dataset creation simulating multiple sensor readings over time.
- **Feature Engineering**: rolling mean, rolling standard deviation for sensor data.
- **Models Implemented**:
  - **XGBoost Regressor** for tabular ML.
  - **LSTM** for time-series prediction.
  - **Transformer** for advanced sequence modeling.
- **Evaluation Metrics**: RMSE, MAE.
- **Interpretability**: SHAP summary and force plots for XGBoost.
- **Model Saving**: XGBoost (joblib), LSTM & Transformer (Keras .h5).
- **Visualization**: Predicted vs Actual RUL for LSTM and Transformer, comparison bar plots.
- Ready-to-run **Colab Notebook** for quick execution and learning.

## Purpose:
- Demonstrates end-to-end predictive maintenance workflow.
- Highlights ability to work with **time-series data**, **ML models**, **Deep Learning**, and **model interpretation**.
- Suitable for showcasing skills in a **portfolio or to potential employers**.

## How to Use:
1. Open the Colab notebook `Predictive_Maintenance_ML_DeepLearning.ipynb`.
2. Run all cells sequentially.
3. Download generated models (`.joblib`, `.h5`) for reuse or further experiments.

## Tech Stack:
- Python, Pandas, NumPy, Scikit-learn
- XGBoost, TensorFlow/Keras
- SHAP for model interpretability
- Matplotlib for visualization
- Google Colab for execution

