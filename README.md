##  Heart Disease Prediction Project

### 🎯 Objective
The goal was to develop a machine learning model that predicts the presence of heart disease using clinical data such as age, sex, chest pain type, blood pressure, cholesterol levels, and more.

---

### 🤖 Models Evaluated
- Logistic Regression
- Naive Bayes
- Support Vector Machine(SVM)
- K Nearest Neighbours (KNN)
- Decision Tree
- Random Forest
- XGBoost
- Neural Network

---

### 📊 Evaluation Metrics
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **AUC-ROC Curve**

---

### 🏆 Best Performing Model
- **Random Forest** achieved the highest **F1 Score**, indicating the best trade-off between precision and recall.
- While models like ** Naive Bayes**, **SVM**, **KNN**, ** Decision Tree**, **XGBoost** and ** Neural Network** showed strong performance, they **did not significantly outperform** Logistic Regression.

---

### 🔍 Key Insights
- Important features: **chest pain type**, **cholesterol**, and **maximum heart rate**.
- Data preprocessing and feature selection played a crucial role in model performance.
- Simpler models can often perform as well or better than complex ones when data is clean.

---

### 🚀 Recommendations for Future Work
- Apply **GridSearchCV** or **Optuna** for hyperparameter tuning.
- Use **k-Fold Cross Validation** to enhance model reliability.
- Explore **model explainability** tools like SHAP or LIME.
- Consider external validation with a larger or real-world dataset.

---

### ✅ Final Verdict
> Despite experimenting with various ensemble techniques, **Random Forest** stood out as the **most reliable, interpretable, and balanced model** for this heart disease prediction task.

