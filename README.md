# Comparative Data-Driven and Mechanistic Tumor Models: Physics-Informed Neural Networks (PINNs) for Tumor Dynamics

This project compares **traditional machine learning models** with **physics-informed neural networks (PINNs)** to predict tumor growth dynamics while incorporating mechanistic biological knowledge. The goal is to evaluate how combining data-driven learning with mechanistic constraints improves prediction accuracy, interpretability, and robustness.

**Repository Contents**
- `data/` – Datasets used for model training and evaluation, including the final tumor growth dataset. Additional datasets (tumor spheroids and survey lung cancer data) are included for reference but were not used in final results due to small size or limited time points.
- `models/` – Trained model files and scripts for ML models and PINNs.
- `notebooks/` – Jupyter notebooks for data preprocessing, model training, PINN implementation, and visualization.
- `figures/` – Plots for tumor growth predictions, model comparisons, and residuals.
- `results/` – Performance metrics, tables, and analysis outputs.
- `ML vs PINNs.zip` – Complete archive of all code, datasets, and plots.
- `requirements.txt` – Python package dependencies.

**Implemented Models**
- Linear Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- Neural Network  
- Physics-Informed Neural Network (PINN)

**Data Notes**
- Final tumor volume dataset used to ensure sufficient time-series for reliable training.  
- Tumor spheroid dataset excluded: dataset too small for PINN learning.  
- Survey-based lung data excluded: Cross-Sectional data.  

**Project Roadmap**
- Preprocess datasets and clean time-series data.  
- Train baseline traditional ML models and evaluate performance.  
- Implement PINNs to embed tumor growth equations into learning.  
- Compare predictions, generate plots, and analyze metrics.  

This repository provides a **reproducible framework** for comparing data-driven and mechanistic approaches to tumor modeling and demonstrates the benefits of **physics-informed neural networks** in capturing biologically meaningful dynamics.
