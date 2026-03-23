# 🏋️ Gym Progress Predictor using Deep Learning

A Deep Learning project that predicts multiple fitness outcomes such as **Weight Change, Muscle Gain, and Fat Loss** using a Multi-Input Multi-Output (MIMO) Neural Network with Hyperparameter Tuning.

---

## 📌 Problem Statement

Tracking gym progress manually is inefficient and often inaccurate. This project uses a **Deep Learning model** to predict multiple fitness metrics based on user lifestyle and workout data.

---

## 🎯 Objectives

- Predict multiple fitness outputs simultaneously
- Use a **Multi-Input Multi-Output Neural Network**
- Optimize performance using **Optuna Hyperparameter Tuning**
- Visualize results using graphs

---

## 🧠 Model Overview

- **Inputs:**
  - Workout Duration (minutes)
  - Calories Intake (kcal)
  - Sleep Hours
  - Training Intensity

- **Outputs:**
  - Weight Change
  - Muscle Gain
  - Fat Loss

- **Techniques Used:**
  - Deep Learning (TensorFlow / Keras)
  - Hyperparameter Optimization (Optuna)
  - Data Scaling (StandardScaler)

---

## 📊 Dataset

A **synthetic but realistic dataset** is generated using mathematical relationships between:
- Workout
- Calories
- Sleep
- Intensity

This simulates real-world gym conditions.

---

## 📈 Visualizations

The project includes:

- Workout vs Weight Change graph  
- Actual vs Predicted comparison  
- Model Loss Curve (Training vs Validation)  

---

## ⚙️ Tech Stack

- Python  
- TensorFlow / Keras  
- Optuna  
- Scikit-learn  
- Matplotlib  
- Google Colab  

---

## 🚀 How to Run

1. Open the notebook in Google Colab  
2. Install dependencies:
   ```bash
   !pip install optuna
