# Diabetes Prediction Model (Project #05)

The fifth project in my **AI/ML Learning Path**. This project marks my transition from Computer Vision to **Supervised Learning on Tabular Data**, focusing on binary classification for healthcare outcomes.

## 📌 Overview
This project uses a medical dataset to predict whether a patient has diabetes based on specific diagnostic measurements. It explores the end-to-end pipeline of a data science project: from data cleaning and EDA (Exploratory Data Analysis) to model deployment.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Algorithms:** Logistic Regression / Support Vector Machine (SVM) / Random Forest (Specify which one you used)

## 📊 Dataset Features
The model analyzes several medical predictor variables, including:
- Glucose levels
- Blood Pressure
- BMI (Body Mass Index)
- Age
- Insulin levels
- Diabetes Pedigree Function

## ⚙️ How It Works
1. **Data Preprocessing:** Handled missing values (often represented as zeros in this dataset) and performed feature scaling using StandardScaler.
2. **Exploratory Data Analysis (EDA):** Visualized correlations between features using heatmaps to understand which health factors most influence diabetes.
3. **Model Training:** Split the data into training and testing sets (80/20) and trained a classifier.
4. **Evaluation:** Measured performance using a Confusion Matrix, Accuracy Score, and Classification Report.

## 🚀 Quick Start
1. **Install Dependencies:**
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
2. **Run the Script:**
   ```bash
   python train.py
   python test.py
3. **Predict:** Input custom medical data into the model to see the predicted outcome.

*Mastered the basics of tabular data and binary classification.*
