# Credit Card Fraud Detection using Sampling Techniques and Machine Learning

## 📌 Project Overview
This project demonstrates the application of **five different sampling techniques** combined with **five machine learning models** on a **credit card transaction dataset**.  
The goal is to analyze how different sampling strategies influence model performance and to identify the most effective sampling–model combinations.

This repository is designed to be **educational, reproducible, and beginner-friendly**, allowing any user to follow the same workflow and recreate the results.

---

## 🎯 Objectives
- Handle class imbalance in a credit card dataset  
- Apply multiple **probabilistic sampling techniques**  
- Train multiple **machine learning models**  
- Compare performance using accuracy  
- Identify the best sampling technique for each model  

---

## 📂 Dataset Description
- **Dataset**: Credit Card Transactions  
- **Target Variable**: `Class`  
  - `0` → Normal transaction  
  - `1` → Fraudulent transaction  
- The dataset was first **balanced** before applying sampling methods.

---

## 🔁 Overall Workflow

```mermaid
flowchart TD
    A[Load Credit Card Dataset] --> B[Balance Dataset]
    B --> C[Apply 5 Sampling Techniques]
    C --> D[Split into Train/Test Sets]
    D --> E[Train 5 ML Models]
    E --> F[Evaluate Accuracy]
    F --> G[Compare Results]
    G --> H[Final Conclusion]
