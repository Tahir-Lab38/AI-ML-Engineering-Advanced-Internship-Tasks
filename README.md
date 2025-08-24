# AI/ML Engineering – Advanced Internship Tasks

This repository contains my internship tasks for the **AI/ML Engineering – Advanced Internship** program.  
Each task demonstrates practical skills in data analysis, machine learning, and building end-to-end pipelines.

---

## 📂 Repository Structure


---

## 📝 Task Descriptions

### 🔹 Task 1 – (Completed Earlier)
- Data exploration and visualization  
- Notebook + dataset included in `Task1/`

---

### 🔹 Task 2 – End-to-End ML Pipeline (Telco Customer Churn) ✅
**Goal:** Build a reusable, production-ready ML pipeline using scikit-learn to predict **customer churn**.  

**Steps performed:**
1. **Data Loading** – `WA_Fn-UseC_-Telco-Customer-Churn.csv`
2. **Data Cleaning** – handled missing values, dropped `customerID`, converted `Churn` to binary labels (0/1).
3. **Feature Engineering** – separated numerical & categorical features.
4. **Pipeline Construction** –  
   - Numeric: Median imputation → StandardScaler  
   - Categorical: Most frequent imputation → OneHotEncoder  
   - Combined via `ColumnTransformer`
5. **Model Training** – Logistic Regression & Random Forest with `GridSearchCV`.
6. **Evaluation** – Metrics (Accuracy, Precision, Recall, F1, ROC-AUC), ROC/PR curves.
7. **Export** – Best model pipeline saved with `joblib` for reuse.

**Key Libraries Used:**
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn (Pipeline, ColumnTransformer, GridSearchCV)

---

### 🔹 Task 3 – (Pending)
Will be added later.

---

## 🚀 How to Run
1. Open the notebook in **Google Colab** or Jupyter Notebook.
2. Upload the dataset `WA_Fn-UseC_-Telco-Customer-Churn.csv` when prompted.
3. Run all cells sequentially.
4. The notebook will output metrics, visualizations, and save the best pipeline model.

---

## 📊 Results (Task 2)
- Built an **end-to-end ML pipeline** for churn prediction.  
- Evaluated Logistic Regression & Random Forest.  
- Achieved strong classification metrics with ROC-AUC > **0.84**.  

---

## 📌 Notes
- Each task is self-contained in its respective folder.  
- Future tasks (Task 3) will be added to this repository.  
