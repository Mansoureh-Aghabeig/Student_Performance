# 📊 Math Score Prediction - End-to-End ML Project 🚀

## 📌 Project Overview
This is an **end-to-end Machine Learning project** that predicts **students' math scores** based on other academic and demographic features. The dataset includes various factors such as **gender, parental education, test preparation courses, and reading/writing scores** to make accurate predictions.

The project follows **a complete Machine Learning pipeline**, including **data preprocessing, feature engineering, model training, hyperparameter tuning, and deployment using Flask**.


---

## 🚀 **Technologies Used**
- **Programming Language:** Python 🐍
- **Machine Learning Libraries:**  
  - `scikit-learn`: ML models (KNN, Decision Trees, Random Forest, AdaBoost, SVM, Linear Regression, Ridge, Lasso)  
  - `XGBoost`, `CatBoost`, `RandomizedSearchCV` for hyperparameter tuning  
- **Data Processing & Visualization:**  
  - `pandas`, `NumPy` for data handling  
  - `Matplotlib`, `Seaborn` for visualization  
- **Model Deployment:** Flask 🌐  
- **Logging & Debugging:** Python `logging` module  
- **Version Control:** Git & GitHub  

---

## 🔎 **Dataset Information**
- **Number of Entries:** `1000`
- **Columns & Data Types:**
  
| # | Column                       | Data Type |
|---|------------------------------|-----------|
| 1 | gender                       | Object    |
| 2 | race_ethnicity               | Object    |
| 3 | parental_level_of_education  | Object    |
| 4 | lunch                        | Object    |
| 5 | test_preparation_course      | Object    |
| 6 | math_score                   | Integer   |
| 7 | reading_score                | Integer   |
| 8 | writing_score                | Integer   |

---

## 🔥 **Key Features**
✅ **Data Preprocessing** - Handles missing values, encoding categorical features, feature scaling  
✅ **Feature Engineering** - Generates meaningful features from the dataset  
✅ **Model Selection** - Trained multiple models & selected the best using `r2_score`, `MSE`, and `MAE`  
✅ **Hyperparameter Tuning** - Used `RandomizedSearchCV` for optimal model parameters  
✅ **Logging & Exception Handling** - Implemented structured logging for debugging  
✅ **Deployment Ready** - Integrated with Flask for real-time predictions  

---

## ⚙️ **How to Run the Project Locally**
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-username/math-score-prediction.git
cd math-score-prediction
