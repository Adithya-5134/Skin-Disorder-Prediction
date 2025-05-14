# 🌟 Skin Disorder Classification 🚀

## 📌 **Project Overview**
Welcome to the **Skin Disorder Classification** project! This machine learning model helps classify different types of skin disorders based on various patient symptoms and clinical features.

## 📂 **Dataset Information**

📄 **File:** Skin_Disease_Dataset.csv

## 📊 **Features:**

- 🧑‍⚕️ **Age:** Age of the patient

- 🚻 **Sex:** Male or Female

- 🧬 **Family History:** Whether the patient has a family history of skin diseases

- 🌡️ **Symptoms:**  
  - Itching  
  - Scaling  
  - Redness  
  - Swelling  
  - Blisters  
  - Burning  
  - Cracks  
  - Peeling  
  - Rash  
  - Ulcers  

- 🎯 **Diagnosis:** Target label indicating the type of skin disorder (multi-class)

## 🔍 **Model Implementation**

📜 **File:** skindisorder_final.ipynb

🛠️ **Steps Followed:**

- 🏗️ **Data Preprocessing** - Cleaning missing data, encoding categorical variables, feature scaling

- 📊 **Exploratory Data Analysis (EDA)** - Visualizing symptom distribution and class imbalance

- 🤖 **Model Selection** - Training and comparing multiple classification models

- 📈 **Model Evaluation** - Accuracy score, confusion matrix, and classification metrics

## 🤖 **Models Used**

- 🔹 Logistic Regression

- 🔹 Decision Tree Classifier

- 🔹 Random Forest Classifier

- 🔹 Support Vector Classifier (SVC)

- 🔹 XGBoost Classifier

- 🔹 K-Nearest Neighbors (KNN) Classifier

- 🔹 MLP Classifier

## 📉 **Metrics Used**

- 📌 Accuracy

- 📌 Precision

- 📌 Recall

- 📌 F1-Score

- 📌 Confusion Matrix

## 🔍 **Hyperparameter Tuning & Optimization**

- ✅ Used RandomizedSearchCV or GridSearchCV for optimal parameter selection

- ✅ Applied k-fold cross-validation to prevent overfitting and ensure model robustness

## 🔑 **Key Insights**

- 🌡️ Symptoms such as itching, redness, and scaling were the most significant predictors

- 🧬 Patients with a family history had a higher likelihood of specific disorders

- 🤖 Ensemble models like Random Forest and XGBoost showed superior classification performance

## 🎯 **Conclusion**

This project effectively classifies various types of skin disorders using machine learning techniques. The Random Forest and XGBoost models delivered the best performance. The analysis reveals that **itching, redness, and family history** are crucial features in accurate diagnosis.
