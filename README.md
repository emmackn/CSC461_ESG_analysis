# ESG Analytics Project — Classification, Clustering & Regression  

This repository contains all the work conducted for our ESG (Environmental, Social, and Governance) machine learning project.  
The objective is to understand whether ESG performance can be predicted using financial, environmental, and structural company indicators — and to evaluate how different ML models behave across classification, clustering, and regression tasks.

---

##  Repository Structure

### **EDA_ESG.ipynb**

### **Clustering_ESG.ipynb**
This notebook explores unsupervised learning techniques to uncover natural groups of companies based on ESG and financial indicators.  
It includes:
- Data preprocessing and feature engineering  
- PCA visualization  
- K-Means, Hierarchical Clustering, and DBSCAN  
- Interpretation of ESG-related grouping patterns  

---

### **Classification_ESG.ipynb**
This notebook focuses on predicting ESG classes (**Low / Moderate / High**) using supervised learning.  
Models implemented include:
- Logistic Regression  
- Decision Trees  
- Random Forest  
- XGBoost  
- Performance metrics, confusion matrices, feature importance  
- Interpretation of model behavior and limitations  

The classification task is one of the project’s two core components and is used in the final presentation.

---

### **Regression_ESG.ipynb**
This notebook analyzes the predictability of continuous outcomes such as:
- **ESG_Overall**
- **MarketCap** (extended regression experiment)

It includes:
- Linear, Ridge, Lasso regression  
- Decision Tree & Random Forest regression  
- Gradient Boosting  
- Residual analysis, interpretation, and links to project question  

---

### **Final Report (PDF)**  
A full written report summarizing:
- Motivation and research questions  
- Dataset description & feature engineering  
- Clustering, classification, and regression methodology  
- Full results with interpretation  
- Critical analysis and limitations  
- Future work  

---

### **company_esg_financial_dataset**  
Our dataset.

---

## Project Goals

- Determine whether ESG performance can be predicted from financial and environmental attributes  
- Understand the structure of ESG-related data using clustering  
- Compare linear and nonlinear models in both classification and regression  
- Evaluate practical implications for ESG analytics and financial decision-making  

---

## Technologies Used  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib / Seaborn  
- Jupyter Notebooks  

---

## Summary  
This repository consolidates the full analytical pipeline — from preprocessing and feature engineering to clustering, classification, regression, and final reporting.  
It reflects the complete progression of the ESG project and serves as a structured, reproducible reference for the final presentation.

---

## Authors
**Emma Choukroun**  
**Peter Card**

Project completed as part of the course **CSC 461 — Machine Learning**.
