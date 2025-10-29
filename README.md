# 💼 Adult Income Prediction Model  

### 📘 Overview  
This project predicts whether an individual earns **more or less than \$50,000 per year** using demographic and employment data from the **UCI Adult Census dataset**.  
It evaluates multiple machine learning algorithms to determine the most effective approach for income classification.

---

### 🎯 Objectives  
- Build a predictive model using demographic and employment-related features.  
- Compare the performance of **Decision Tree**, **Random Forest**, and **Support Vector Machine (SVM)**.  
- Identify key factors influencing income level.  
- Evaluate models using standard performance metrics.

---

### ⚙️ Workflow  

#### 1. Data Preprocessing  
- Handled missing and inconsistent entries.  
- Encoded categorical variables such as gender, education, and occupation.  
- Normalized numerical variables for optimal model performance.

#### 2. Model Development  
- Implemented **Decision Tree**, **Random Forest**, and **SVM** classifiers.  
- Tuned hyperparameters using **GridSearchCV** for optimal accuracy.

#### 3. Model Evaluation  
- Compared results using **Accuracy**, **Precision**, **Recall**, **F1-score**, and **ROC-AUC**.  
- Visualized confusion matrices and feature importance plots.

---

### 🧠 Tools & Libraries  
- **Python**  
- **Pandas**, **NumPy**, **Scikit-learn**  
- **Matplotlib**, **Seaborn**

---

### 📊 Results  
- **Random Forest** delivered the best performance overall.  
- **SVM** showed strong performance after feature normalization.  
- Most influential features: **educ**

