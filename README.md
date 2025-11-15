# Advanced Ensemble Learning & Explainability for Car Price Prediction

### Author: Paramesh Kumar Bukya  
*MSc Data Science (Distinction), Manchester Metropolitan University*

---

## 📘 Project Overview

This project extends the car price prediction workflow using advanced machine learning techniques, including ensemble models and explainability tools (SHAP & PDP). It builds on real-world data provided by AutoTrader UK under a confidential partnership with Manchester Metropolitan University.

The notebook demonstrates:

- Automated & domain-based feature engineering  
- Polynomial features  
- Feature selection (RFE, SelectKBest)  
- PCA (tested)  
- Random Forest, Gradient Boosting, Linear Regression  
- Ensemble learning via Voting Regressor  
- SHAP & Partial Dependence Plots  

---

## 🔒 Dataset Access (Important)

The dataset used in this project (`adverts.csv`) is **confidential** and cannot be shared publicly.  
It was provided under an academic partnership between **MMU and AutoTrader UK**.

➡️ Therefore, the dataset is **NOT included** in this repository.

### To run the notebook:

1. Upload your authorised `adverts.csv` file to the same folder as the notebook  
2. If necessary, install missing libraries:  
   ```bash
   pip install numpy pandas scikit-learn seaborn matplotlib shap category_encoders
