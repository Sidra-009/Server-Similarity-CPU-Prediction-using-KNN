# 🖥️ Server Similarity & CPU Prediction using KNN

## 📖 Project Overview
This project simulates server performance data (CPU, Memory, Network Traffic) for multiple servers across several time intervals and applies **K-Nearest Neighbors (KNN)** for similarity analysis and CPU usage prediction. It demonstrates how KNN can be used in a real-world server monitoring scenario for both similarity detection and forecasting.

---

## ✨ Features
- **🖥️ Server Data Simulation**: Generates CPU (%), Memory (%), and Network Traffic (Mbps) data for multiple servers across 5 time intervals.
- **🔍 KNN Similarity Analysis**: Finds similar servers based on combined features (CPU, Memory, Network).
- **📊 Visualization**:
  - Heatmaps for CPU, Memory, and Network usage.
  - Euclidean distance matrix to show server similarity.
  - Clustermap for server similarity clusters.
- **📈 CPU Prediction**: Uses KNN Regression to predict CPU usage at the next time interval.
- **📉 Prediction Visualization**: Plots predicted vs actual CPU usage for each server.

---

## 🛠️ Libraries Used
- `numpy` – For numerical operations and data simulation.
- `pandas` – For structured data handling.
- `scikit-learn` – For KNN similarity and regression.
- `matplotlib` & `seaborn` – For data visualization.

---

