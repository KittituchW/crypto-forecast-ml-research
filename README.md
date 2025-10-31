# 36120-25SP AT3 — Group 13 — Crypto Investment Data Product

This repository contains the **final data product** for **Assessment Task 3 (AT3)** in *Advanced Machine Learning Application (36120)*.  
Our project builds a **Streamlit-based web application** that helps users make informed decisions when investing in cryptocurrencies using **machine learning predictions**.

---

## 1. Project Overview

We developed an **interactive crypto investment platform** that:
- Predicts **next-day HIGH prices** for selected cryptocurrencies.
- Visualises **price trends, volatility, and feature insights**.
- Integrates **ML models**, **FastAPI endpoints**, and **Streamlit UI** in a complete pipeline.

Each group member contributed a model using a specific **algorithm** and **cryptocurrency**, and these models were integrated into the final product.

---

## 2. Key Components

| Component | Description |
|------------|-------------|
| **Data Preparation** | Preprocessed daily OHLCV data from the CryptoCompare API. |
| **Feature Engineering** | Generated time-based, trend, and volatility features for model training. |
| **Model Training** | Each member trained and tuned a model for their chosen cryptocurrency. |
| **Model Integration** | Best-performing models saved as artefacts (`.joblib`) and loaded in Streamlit. |
| **Visualization** | Implemented interactive charts for model results and historical analysis. |
| **Deployment** | Streamlit frontend and FastAPI backend integrated for real-time predictions. |

---

## 3. Repository Structure
---
AMLA_AT3_GROUP13/
├─ data/
│ ├─ raw/ # original OHLCV data
│ └─ processed/ # cleaned and feature-engineered datasets
├─ models/ # trained artefacts (.joblib, .json)
├─ notebooks/ # individual experiments and EDA notebooks
├─ reports/
│ ├─ figures/ # plots for report and presentation
│ └─ final_report.pdf
├─ tests/
├─ docs/
├─ pyproject.toml
├─ requirements.txt # environment dependencies (pinned versions)
├─ Makefile
├─ github.txt # private repo link
└─ README.md

---

## ⚙️ 4. Requirements

The assignment requires these versions:

- Python **3.11.4**
- pandas **2.2.2**
- scikit-learn **1.5.1**
- xgboost **2.1.0**
- lightgbm **4.4.0**
- hyperopt **0.2.7**
- jupyterlab **4.2.3**
- joblib **1.4.2**
- streamlit **1.36.0**
- lime **0.2.0.1**
- wandb **0.17.4**


---