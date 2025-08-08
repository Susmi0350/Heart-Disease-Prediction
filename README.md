
#  Heart Disease Prediction using Logistic Regression

This project focuses on building a machine learning model to predict the presence of heart disease in a patient using clinical data. The dataset used is a structured dataset that contains a variety of features collected from patients, such as age, cholesterol levels, blood pressure, and more.

---

## 📌 Table of Contents

1. [Introduction](#introduction)  
2. [Dataset Description](#dataset-description)  
3. [Techniques Used](#techniques-used)  
4. [Data Preprocessing](#data-preprocessing)  
5. [Model Building](#model-building)  
6. [Evaluation Metrics](#evaluation-metrics)  
7. [Results & Insights](#results--insights)  
8. [Conclusion](#conclusion)

---

## 🔍 Introduction

Heart disease remains one of the leading causes of death worldwide. Early prediction using patient data can help in timely intervention. This project uses logistic regression to classify whether a patient has heart disease or not, based on medical features.

---

## 📊 Dataset Description

The dataset was loaded from a CSV file named `heart_disease_data.csv`.

### Features:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Serum Cholesterol
- Fasting Blood Sugar
- Resting Electrocardiographic Results
- Max Heart Rate Achieved
- Exercise-Induced Angina
- ST Depression (oldpeak)
- Slope of Peak Exercise ST Segment
- Number of Major Vessels Colored by Fluoroscopy
- Thalassemia

### Target:

- `0`: Healthy  
- `1`: Heart Disease

---

## 🛠 Techniques Used

- **Language**: Python
- **Libraries**: NumPy, Pandas, Scikit-learn
- **Model**: Logistic Regression
- **Validation**: Accuracy score on training and testing sets

---

## 🧹 Data Preprocessing

- Loaded CSV into a pandas DataFrame.
- Displayed first and last few rows using `.head()` and `.tail()`.
- Inspected data types and null values using `.info()` and `.isnull().sum()`.
- Generated descriptive statistics with `.describe()`.
- Split data into features (X) and target (Y).
- Checked target value distribution using `.value_counts()`.

---

## 🧪 Model Building

1. **Train-Test Split**  
   - 80% training and 20% testing data  
   - `stratify=Y` to maintain class balance  
   - `random_state=2` for reproducibility  

2. **Logistic Regression Model**  
   - Fitted using Scikit-learn's `LogisticRegression()`  
   - Trained on the training set  

---

## 📈 Evaluation Metrics

- **Accuracy Score**:  
  - Computed for both training and test predictions using `accuracy_score()`.

---

## 🔎 Results & Insights

- The model was able to classify patients effectively using logistic regression.
- Balanced dataset with both classes well-represented.
- Accuracy metrics suggest the model generalizes reasonably well to unseen data.

---

## ✅ Conclusion

This project demonstrates that even a simple logistic regression model can be effective in medical classification problems like heart disease detection. With proper data preprocessing and evaluation, interpretable models can achieve good performance in critical applications.
