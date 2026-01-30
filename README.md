# AI-ML Internship – Task 7  
## Logistic Regression – Titanic Survival Prediction

---

## 📌 Objective  
The objective of this task is to build a **Logistic Regression classification model** to predict passenger survival on the Titanic dataset and evaluate it using standard classification metrics and ROC-AUC analysis.

---

## 📂 Dataset  
**Titanic Dataset** (loaded using Seaborn)

- Contains passenger information such as age, sex, fare, and embarkation port
- Target variable: `survived`
  - `1` → Survived  
  - `0` → Not Survived  

---

## 🛠 Tools & Libraries Used  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔍 Steps Performed

### 1. Dataset Loading  
- Loaded the Titanic dataset using `seaborn.load_dataset()`
- Selected relevant features for model training

---

### 2. Data Preprocessing  
- Handled missing values:
  - `age` filled using median
  - `embarked` filled using mode
- Encoded categorical features using One-Hot Encoding
- Applied feature scaling on numerical columns

---

### 3. Train–Test Split  
- Split data into training and testing sets (80% train, 20% test)
- Used stratified sampling to preserve class distribution

---

### 4. Model Training  
- Trained a **Logistic Regression** model
- Increased maximum iterations to ensure convergence

---

### 5. Prediction  
- Generated class predictions
- Generated predicted probabilities for ROC-AUC calculation

---

### 6. Model Evaluation  
The model was evaluated using the following metrics:

- **Accuracy** – Overall correctness of predictions  
- **Precision** – Correctness of positive predictions  
- **Recall** – Ability to identify actual survivors  
- **F1-score** – Balance between precision and recall  

A **confusion matrix** was plotted to visualize classification results.

---

### 7. ROC Curve and AUC Score  
- Plotted the ROC curve to analyze trade-off between true positive and false positive rates
- Calculated **AUC score** to measure overall classification performance

---

## 📦 Deliverables  
- ✔ Jupyter Notebook (.ipynb)  
- ✔ Confusion Matrix plot  
- ✔ ROC Curve plot  
- ✔ AUC score  

---

## 🎯 Final Outcome  

The intern successfully built a complete **binary classification model**, evaluated it using multiple metrics including **ROC-AUC**, and gained a strong understanding of classification performance evaluation and interpretation.

---
