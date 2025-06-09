# 📡 Intelligent Service Placement on Mobile Edge Nodes

🎓 Final Year Project – Academic Year 2024/2025  
📍 International Institute of Technology, Sfax, Tunisia  



---

## 📘 Project Overview

This project presents a proactive and intelligent strategy to **dynamically deploy services on Edge nodes** in a mobile and dynamic environment — such as **autonomous vehicles**.

✅ Goals:
- Predict Quality of Service (QoS) parameters (latency, CPU load, etc.)
- Anticipate degradation
- Select the optimal Edge node in real time

---

## ⚙️ Technology Stack

| Layer          | Technology        |
|----------------|-------------------|
| Backend        | FastAPI (Python)  |
| Frontend       | Angular           |
| Database       | Firebase          |
| AI/ML          | Transformer, GRU, AutoGluon |
| Visualization  | Chart.js          |
| Tools          | Google Colab, VS Code |

---

## 🏗️ System Architecture

The architecture consists of four main modules:

- **Data Collector**: Captures real-time QoS metrics from Edge nodes
- **Predictive Model (Transformer)**: Forecasts performance trends
- **Decision Engine**: Selects the best node based on predicted metrics
- **Deployment Interface**: Transfers services to the selected node

![image](https://github.com/user-attachments/assets/a5f26853-50e0-4887-bc07-7d1125e1220a)


---

## 🧩 Frontend Architecture

The frontend is built using Angular and provides:

- A **monitoring dashboard** with live charts
- A **map of Edge nodes**
- A **node recommendation interface**
- **User authentication** via Firebase

![image](https://github.com/user-attachments/assets/9314d7a3-231d-4648-9173-2f261badaf51)



---

## ✨ Features

- 🔮 QoS Prediction using GRU/Transformer
- 📍 Intelligent Node Selection (AutoML / AutoGluon)
- 📊 Real-Time Monitoring Dashboard
- 🔐 User Authentication with Firebase
- 🌍 Geographical Filtering with EdgeOnto Ontology

---

## 🧪 Results Summary

| Model        | Accuracy (%) | F1-score |
|--------------|--------------|----------|
| GRU          | 87.5         | 0.86     |
| Transformer  | 89.1         | 0.88     |
| AutoGluon    | **94.15**    | **0.934**|

✅ The AutoGluon model gave the best results, combining multiple classifiers with stacking.

---

## 📂 Project Structure

```bash
📁 project-root/
├── backend/
│   ├── main.py
│   └── models/
├── frontend/
│   └── src/
│       └── app/
├── dataset/
│   └── synthetic_qos_data.csv
├── images/
│   ├── architecture.png
│   ├── frontend_architecture.png
│   ├── dashboard.png
│   └── node_selection.png
└── README.md
