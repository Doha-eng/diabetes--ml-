# Diabetes Prediction with Machine Learning

This project uses the **Pima Indians Diabetes dataset** to predict whether a patient has diabetes.  
The main focus is on improving **recall** (catching as many diabetic cases as possible).  
A simple **Gradio web app** is also included for interactive predictions.

---

## 📂 Project Files
- `diabetes.ipynb` → Notebook with preprocessing, training, and evaluation.  
- `model.pkl` → Saved trained model.  
- `scaler.pkl` → Saved StandardScaler for preprocessing.  
- `app.py` → Gradio app to run the model.  
- `requirements.txt` → Project dependencies.  
- `README.md` → Project documentation.  

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
pip install -r requirements.txt




==========================================================================================
 Run Notebook

Train and evaluate different models: RandomForest, KNN with GridSearchCV, XGBoost

==========================================================================================
Models Implemented

Random Forest

KNN

XGBoost

GridSearchCV (for hyperparameter tuning)

Metrics: Accuracy, Recall, Precision, F1-score

=========================================================================================

Input Features

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Output:

Diabetic ✅ or Not Diabetic ❌
======================================================================================

 Requirements

scikit-learn

pandas

matplotlib

seaborn

numpy

xgboost

gradio

joblib
=====================================================================================
 Author
Developed by
Doha Medhat
Tasnim Mostafa 
