# Kidney Disease Classification using Decision Tree

This project analyzes a kidney disease dataset and builds a predictive model using a **Decision Tree Classifier** to identify whether a patient is likely to have chronic kidney disease (CKD). The workflow includes data cleaning, visualization, and classification model training.

## 📊 Project Objectives

- Explore the kidney disease dataset
- Clean and preprocess the data
- Visualize important patterns and correlations
- Build and evaluate a Decision Tree Classifier

## 🧰 Tools & Libraries

- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib**, **Seaborn** for visualization
- **Scikit-learn** for modeling and evaluation

## 🗂️ Dataset

- **File:** `kidney_disease.csv`
- **Source:** Public dataset on kidney health metrics
- **Features include:** blood pressure, albumin, red blood cells, sugar, blood urea, etc.
- **Target Variable:** Classification of chronic kidney disease (CKD or not)

## 🔍 Key Steps

1. **Data Loading & Cleaning**
   - Load dataset using `pandas`
   - Handle missing values and inconsistent formats

2. **Exploratory Data Analysis**
   - Visualize feature distributions and detect outliers
   - Examine correlations between features

3. **Feature Engineering**
   - Convert categorical variables
   - Encode target variable
   - Normalize/scale data if required

4. **Modeling: Decision Tree Classifier**
   - Train-test split
   - Fit Decision Tree model
   - Evaluate using accuracy, confusion matrix, precision, recall, and F1-score

5. **Visualization**
   - Plot feature importances
   - Visualize decision tree structure

## 📈 Evaluation Metrics

- **Accuracy**
- **Precision & Recall**
- **F1-Score**
- **Confusion Matrix**


## ✅ Results

The Decision Tree model achieved satisfactory performance and highlighted key features contributing to kidney disease classification, such as:
- Blood pressure
- Albumin level
- Sugar level
- Red blood cell count

## 🚀 Future Work

- Apply other classification models (Random Forest, SVM, XGBoost)
- Perform hyperparameter tuning

