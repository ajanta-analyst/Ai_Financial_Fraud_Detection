# AI Fraud Detection — Financial Transactions Dashboard (Streamlit)

A lightweight **AI-powered Streamlit dashboard** designed to predict and visualize **fraudulent financial transactions** in real time.  
Built using **Python**, **Scikit-learn**, and **Streamlit**, this project demonstrates how machine learning models detect evolving fraud patterns and communicate insights through a simple, intuitive interface for **non-technical business users**.

---

## Dashboard  
- **Dashboard (view/demo):** https://drive.google.com/file/d/1JWaJIeVGvfAo7VDaIDbCrTeHsE_qf19f/view?usp=sharing

- ![Dashboard Preview](?raw=true)

---

## Table of Contents  
- [About the Project](#about-the-project)  
- [Dataset](#dataset)  
- [Business Questions](#business-questions)  
- [Features & KPIs](#features--kpis)  
- [Steps Followed](#steps-followed)  
- [Outcome](#outcome)  
- [Contact](#contact)

---

## About the Project  
**Goal:** Build an **AI-driven fraud detection dashboard** that helps analysts identify and interpret potential fraud risks in real time — across multiple dimensions such as device type, transaction type, direction, and location.  
**Tech:** Python · Streamlit · Scikit-learn · Pandas · Matplotlib · Joblib.  
**Model:** Logistic Regression (trained and deployed for interactive prediction).  
**Brand:** **AI Fraud Detection for Financial Transactions** (Portfolio Project).

---

## Dataset  
Columns used:  
- `Transaction ID`, `Transaction Type`, `Transaction Direction`, `Device Type`, `Location`, `Amount`, `Fraud Flag`.  

> The dataset is a **synthetic portfolio dataset** generated for model experimentation and demonstration of financial fraud prediction workflows.

---

## Business Questions  
1. How accurately can AI detect **fraudulent transactions** across multiple customer touchpoints?  
2. Which **transaction types** (e.g., purchase, withdrawal, transfer, refund) are most prone to fraud?  
3. How do **device type** and **transaction direction (incoming vs outgoing)** correlate with fraud likelihood?  
4. Are certain **locations or branches** showing higher fraud concentration?  
5. How can this model and dashboard be scaled for **real-time fraud monitoring** in enterprise systems?

---

## Features & KPIs  
- **AI Model Integration:** Logistic Regression trained on labeled financial data for binary fraud prediction.  
- **Real-time Prediction:** User inputs transaction details → model predicts fraud probability instantly.  
- **Multi-dimensional Visuals:** Charts showing **Device Type vs Fraud Flag**, **Transaction Type vs Fraud Flag**, **Location vs Fraud Flag**, and more.  
- **Streamlit Interface:** Intuitive and interactive app layout built with Streamlit components.  
- **Scalable Deployment:** Model serialized using **Joblib** and integrated seamlessly into the dashboard.  
- **Performance Metrics:** Accuracy, Precision, Recall, and F1-Score for evaluation.  
- **Color-coded Risk Visualization:** Fraud likelihood shown via colored bars for faster decision-making.  

---

## Steps Followed  

**1) Data Preparation**  
- Imported the dataset using **Pandas** and handled missing or unbalanced values.  
- Performed **encoding** for categorical variables (device type, location, transaction type).  
- Split data into training and testing sets (80:20) for model development.  

**2) Model Building**  
- Trained a **Logistic Regression** classifier using Scikit-learn.  
- Tuned hyperparameters for optimal fraud classification performance.  
- Evaluated model using **Confusion Matrix**, **ROC Curve**, and **Classification Report**.  

**3) Streamlit App Development**  
- Designed an interactive dashboard using **Streamlit**.  
- Built multiple chart sections:  
  - **Device Type vs Predicted Fraud Flag**  
  - **Location vs Predicted Fraud Flag**  
  - **Transaction Type vs Predicted Fraud Flag**  
  - **Transaction Direction vs Predicted Fraud Flag**  
- Enabled file upload for batch predictions.  

**4) Visualization**  
- Used **Matplotlib** and **Seaborn** for clean bar and heatmap visuals.  
- Added legends, tooltips, and risk color indicators.  
- Designed an easy navigation sidebar for model explanation, input forms, and results summary.  

**5) Deployment**  
- Saved trained model using **Joblib**.  
- Deployed the Streamlit app locally and exported as a shareable `.py` dashboard script.  
- Prepared documentation for setup (`requirements.txt`) and model usage.  

---

## Outcome  
A **lightweight AI Fraud Detection dashboard** built with **Streamlit**, providing an intuitive interface for non-technical analysts to explore fraud risk in real time.  
The project showcases how **AI models adapt to evolving fraud patterns** and visualize multi-dimensional insights across **devices**, **locations**, and **transaction types** — bridging the gap between **data science and financial risk management**.

---

