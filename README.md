# Azure-Based Demand Forecasting & Capacity Optimization System (Backend)

## 📘 Overview
This repository contains my backend work for the **Infosys Springboard Virtual Internship (Batch 4)**.  
The project aims to build an **Azure-based system** that predicts resource demand and optimizes capacity using machine learning.

## 🧩 Role
**Team:** B (Backend)  
**Responsibility:** Data cleaning, preprocessing, merging Azure usage with external datasets, and creating REST APIs for usage trends and forecasts.

## 🧰 Tech Stack
- **Python** (pandas, numpy, matplotlib, seaborn)
- **Flask** (for REST APIs)
- **Google Colab** (for EDA & data cleaning)
- **GitHub** (for version control)
- **Azure ML Studio** (for deployment in later milestones)

## 🧪 Milestone 1 Goals
- [x] Set up Python environment  
- [x] Perform EDA on Azure & external datasets  
- [x] Clean and merge data → `data/processed/cleaned_merged.csv`  
- [x] Build dummy REST API (`/api/usage-trends` & `/api/forecast`)  


| Step                   | Description                                                                                                      |  
| ---------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Data Collection        | Sourced Azure historical usage data and external factors (weather, events, electricity prices)                   |
| Data Cleaning          | Handled missing values, removed duplicates, standardized date/time, normalized units                             |
| Data Integration       | Merged datasets by date and region; saved asdata/processed/cleaned_merged.csv                                    |
| Exploratory Analysis   | Computed average daily CPU, monthly peak, and top-5 regional usage; created basic plots with Matplotlib/Seaborn  |


🧑‍💻 Tech Stack

- **Python 3.8+**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **(Upcoming: Flask/FastAPI for REST APIs, scikit-learn, XGBoost, TensorFlow/Keras)**

Integrated_Forecasting_-Predict_Azure_consumer_demand/
├── 📊 FRONTEND/
│   └── dashboard_app.py              # Streamlit Dashboard (266KB)
├── 🔧 BACKEND AUTOMATED REPORTS/
│   ├── intelligent_training_report    #report details of training
│   ├── model_training_pipeline.py   # ML Training Pipeline (42KB)
│            
├── 📦 DATA/
│   └── cleaned_merged.csv            # Historical Dataset (59KB)
├── 🛠️ TOOLS/
│   ├── requirements.txt              # Python Dependencies
│   ├── postman_collection.json      # API Testing Suite
│   └── presentation_materials/      # Demo & Documentation
├── 📚 DOCS/
|   ├── README.md                     # Project Documentation
|   ├── API_DOCUMENTATION.md          # Complete API Reference
|   └── DEPLOYMENT_GUIDE.md           # Production Setup Guide
|
├─── 📊 FRONTEND -dashboard_app.py              # Streamlit Dashboard (266KB)
|─── 🔧 BACKEND -optimised_backend_app.py      # Flask REST API (150KB)
|─── 🔧 BACKEND -model_training_pipeline.py   # ML Training Pipeline (42KB)
|─── 🔧 BACKEND -start_pipeline.py            # System Launcher (1KB)


Yash Bagde
B.Tech, Computer Science Engineering
Email: yash.bagde.work@gmail.com

LinkedIn: https://www.linkedin.com/in/yash-0613-bagde/

GitHub: Yash06-blip
