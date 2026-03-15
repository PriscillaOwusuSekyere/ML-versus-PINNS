# Comparative Data-Driven and Mechanistic Tumor Models: Physics-Informed Neural Networks (PINNs) for Tumor Dynamics

This project compares **traditional machine learning models** with **physics-informed neural networks (PINNs)** to predict tumor growth dynamics while incorporating mechanistic biological knowledge. The goal is to evaluate how combining data-driven learning with mechanistic constraints improves prediction accuracy, interpretability, and robustness.


**Implemented Models**
- Linear Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- Neural Network  
- Physics-Informed Neural Networks (PINNs)

**Data Notes**
- Final tumor volume dataset used to ensure sufficient time-series for reliable training.  
- Tumor spheroid dataset excluded: dataset too small for PINN learning.  
- Survey-based lung data excluded: Cross-Sectional data.  

**Project Roadmap**
Install latest version Jupyter notebook or Python
- Preprocess datasets and clean time-series data.  
- Train baseline traditional ML models and evaluate performance.  
- Implement PINNs to embed tumor growth equations into learning.  
- Compare predictions, generate plots, and analyze metrics.  

This repository provides a **reproducible framework** for comparing data-driven and mechanistic approaches to tumor modeling and demonstrates the benefits of **physics-informed neural networks** in capturing biologically meaningful dynamics.
