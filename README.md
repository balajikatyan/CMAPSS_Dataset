## 📌 Project Overview
Predicting the **Remaining Useful Life (RUL)** of aircraft engines is crucial for **predictive maintenance** in aviation. This project leverages **Long Short-Term Memory (LSTM)** networks to analyze time-series sensor data from the **C-MAPSS dataset** and estimate the number of operational cycles before an engine fails.

## 📂 Dataset: C-MAPSS
The **C-MAPSS (Commercial Modular Aero-Propulsion System Simulation) dataset** is widely used for **prognostics and health management (PHM)** tasks. It contains multivariate sensor readings from multiple engines operating under different conditions.

### 📊 Features:
- **21 Engine Sensors** (Temperature, Pressure, Fan Speed, etc.)
- **Operating Conditions** (Altitude, Mach Number, etc.)
- **Engine Cycles** (Time-series degradation patterns)
- **RUL Labels** (Ground truth for training and evaluation)

## 🚀 Model: LSTM-based Time Series Prediction
LSTM networks are chosen due to their ability to capture **long-term dependencies** in sequential data. The model takes historical sensor readings and predicts the **RUL** at each time step.

### **Architecture:**
✔ **LSTM Layers** for sequence learning  
✔ **Dropout Layers** for regularization  
✔ **Dense Layers** for RUL regression  
✔ **Mean Squared Error (MSE)** as the loss function  

## Results:
![image](https://github.com/user-attachments/assets/1f7aa813-243b-4973-b82d-96e5f935991b)
![image](https://github.com/user-attachments/assets/dcccdca8-3a28-4441-9400-ae0d202fca5f)

