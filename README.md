# 🍷 Wine Quality Predictor  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg?logo=python&logoColor=white)  
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange.svg?logo=scikit-learn&logoColor=white)  
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg?logo=jupyter&logoColor=white)  
![License](https://img.shields.io/badge/License-MIT-green.svg)  

This project uses the **Red Wine Quality dataset** from the UCI Machine Learning Repository to build a machine learning model that predicts wine quality based on physicochemical properties such as acidity, sugar, pH, and alcohol.  

---

## 📊 Dataset  
- **Source:** [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)  
- **Records:** 1,599 red wine samples  
- **Features:** 11 physicochemical attributes (e.g., fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol)  
- **Target:** Quality score (0–10) assigned by wine experts  

---

## ⚙️ Project Workflow  
1. Data preprocessing & cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature selection & scaling  
4. Model training (classification/regression approaches)  
5. Model evaluation (accuracy, confusion matrix, etc.)  

---

## 🧠 Machine Learning Models  
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  
- Neural Networks (optional, depending on your notebook)  

---

## 🚀 Results  
The model predicts wine quality with reasonable accuracy and highlights the influence of **alcohol, sulphates, and acidity** as key factors.  

---

## 📦 Installation  
Clone the repo and install dependencies:  
```bash
git clone https://github.com/yourusername/wine-quality-predictor.git
cd wine-quality-predictor
pip install -r requirements.txt
```
---
## ▶️ Usage
Run the Jupyter Notebook to train and test the model:
```bash
jupyter notebook COMP-FINAL-PROYECT.ipynb
```
---
## 📌 Future Improvements
-  Hyperparameter tuning
-  Integration with a web app for real-time predictions
-  Extend to white wine dataset
---
## 📖 References
-  UCI Machine Learning Repository – Wine Quality
-  Cortez et al., 2009: Modeling wine preferences by data mining from physicochemical properties
---
