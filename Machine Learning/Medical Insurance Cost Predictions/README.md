# 🏥 Medical Insurance Cost Prediction


## 📌 Overview
This project aims to predict individual medical insurance costs using Machine Learning models trained on personal health data. The dataset includes features such as age, sex, BMI, number of children, smoking status, and region.


---
## 🔍 Problem Statement
Accurately predicting medical insurance costs is crucial for insurance companies to set fair premiums and for individuals to understand potential expenses. This project builds a predictive model to estimate insurance charges based on personal attributes.

---
## 📊 Data Preprocessing & Feature Engineering

 * Missing Values Handling:
     *Verified that the dataset has no missing values.
 * Feature Engineering:
     * One-Hot Encoding: Converted categorical variables (sex, smoker, region) into numerical format.
 * Outlier Removal:
      * Analyzed distributions to identify and handle potential outliers in bmi, age, and charges.

---
## 🏆 Machine Learning Models & Cross-Validation Performance


|  Model                           |  Cross-Validation R² Score (%)  |
|----------------------------------|---------------------------------|
|Linear Regression               | 74.35%
|Decision Tree Regression     | 61.91%
|Random Forest Regression          | 78.79%
|Support Vector Regression (SVR)  | -9.36%
|**CatBoost Regression (Best Model) 🏆**          | 79.33%
K-Nearest Neighbors (KNN)          | 10.84%

* Best Model: ✅ Catboost Regressor with 99.64% accuracy

---
## 📂 Dataset Details
 * Dataset Name: insurance
 * Source: Kaggle Dataset
 * Columns: age, sex, bmi, children, smoker, region, charges. 

---
## 📊 Model Evaluation Metrics
 * R² Score: Measures the proportion of variance explained by the model.
 * Root Mean Squared Error (RMSE): Indicates the average deviation of predictions from actual values.

---
## 🛠 Technologies Used
    🔹 Python 
    🔹 Pandas, NumPy – Data preprocessing
    🔹 Matplotlib, Seaborn – Data visualization
    🔹 Scikit-Learn, XGBoost – Machine Learning models
    🔹 Jupyter Notebook

---
## 🚀 How to Use
   * 1️⃣ Navigate to the Medical Insurance Cost.
   * 2️⃣ Open the notebook.ipynb file in Jupyter Notebook.
   * 3️⃣ Run the notebook to train models and predict insurance cost.
----
## 📌 Business Impact
   * 📈 This model assists insurance companies in setting accurate premiums and helps individuals anticipate medical expenses based on personal health factors.









