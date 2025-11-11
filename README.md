# UPI Payment Fraud Detection 🔍  
A machine learning project to detect fraudulent transactions in UPI (Unified Payments Interface) data.

## 🧠 Project Overview  
This repository contains a complete workflow for detecting fraud in digital payment transactions via UPI. The goal is to create a model that can distinguish between legitimate and fraudulent transactions, and to provide a user-friendly interface for demonstration.

## 📂 Contents  
- `UPI_Dataset.csv` — the dataset of UPI transactions used for training and testing.  
- `UPI_FRAUD_DETECTION_PROJECT.ipynb` — the Jupyter notebook containing data exploration, preprocessing, feature engineering, model training, evaluation and final model serialization.  
- `UPI Fraud Detection Final.pkl` — the serialized/trained model ready for inference.  
- `streamlit_app.py` — a simple web app built with Streamlit for interacting with the trained model (uploading transaction data and getting predictions).  
- `requirements.txt` — list of dependencies and Python packages required to run the project locally.  

## 🚀 Features  
- Exploratory Data Analysis (EDA) to explore transaction behaviour and fraud patterns  
- Data preprocessing steps: missing values handling, encoding, scaling, balancing classes etc  
- Feature engineering tailored for fraud detection in UPI data  
- Training of one or more supervised machine learning models (e.g., logistic regression, random forest, XGBoost)  
- Model evaluation with relevant metrics (accuracy, precision, recall, F1-score, ROC-AUC)  
- Deployment of the trained model via a simple Streamlit app for interactive use  
- Ready-to-use trained model file for quick inference  

## 🎯 Why This Project Matters  
With the growth of digital payments, especially via UPI in India, fraudulent transactions have become an increasing risk. A system that can proactively detect fraudulent transaction behaviour offers significant value to payment platforms, banks, and users. This project demonstrates how machine learning can be applied to real‐world financial data for enhanced security and trust.

## 🧑‍💻 How to Run It Locally  
1. Clone the repository:  
   ```bash
   git clone https://github.com/arushiali/upi-payment-fraud-detection.git
   cd upi-payment-fraud-detection
Install dependencies (preferably in a virtual environment):

pip install -r requirements.txt


To run the Jupyter notebook:

jupyter notebook UPI_FRAUD_DETECTION_PROJECT.ipynb


To launch the Streamlit app:

streamlit run streamlit_app.py


Upload or input a transaction record and get prediction: Fraud or Legit.

Future Improvements

Use larger or more recent UPI transaction datasets if available

Incorporate real‐time feature engineering (time of day, transaction networks)

Experiment with deep learning models like LSTM for sequential transaction data

Implement API backend (Flask/FastAPI) and deploy as microservice

Add logging, alerts and dashboard for monitoring live transactions
