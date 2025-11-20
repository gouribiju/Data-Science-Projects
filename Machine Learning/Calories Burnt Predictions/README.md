# 🔥 Calories Burnt Prediction


## 📌 Overview
This project predicts the calories burned during various physical activities based on both body metrics (age, gender, height, weight) and exercise intensity factors (duration, heart rate, MET values).Using Machine Learning, the model identifies how different attributes influence calorie expenditure.

---
## 🔍 Problem Statement
Accurately estimating calorie burn is essential for fitness tracking, personalized workout recommendations, and weight management.
The goal of this project is to build a predictive ML model that estimates calories burned based on user characteristics and activity details.

---
## 📊 Data Preprocessing & Feature Engineering

 * Missing Values Handling:
     * Checked and validated data integrity.
     * Ensured no missing or inconsistent values.
 * Feature Engineering:
     * Created new feature BMI from height and weight.
     * Scaled numerical features using StandardScaler.

 * Outlier Removal:
      * Applied Interquartile Range (IQR) method to filter extreme values in Calories_Burnt, Heart_Rate, and Exercise_Duration.

---
## 🏆 Machine Learning Models & Cross-Validation Performance


|  Model                           |  Cross-Validation R² Score (%)  |
|----------------------------------|---------------------------------|
|Linear Regression               | 98.02%
|Decision Tree Regression     | 93.07%
|Random Forest Regression          | 96.88%
|Support Vector Regression (SVR)  | 0.46%
|**CatBoost Regression (Best Model) 🏆**          | 99.64%
K-Nearest Neighbors (KNN)          | 41.51%

* Best Model: ✅ Catboost Regressor with 99.64% accuracy
* Hyperparameter Tuning: 🎯 Catboost improved after tuning

---
## 📂 Dataset Details
 * Dataset Name: gym_members_exercise_tracking
 * Source: Kaggle Dataset
 * Columns: Age, Gender, Weight (kg), Height (m), Max_BPM,Avg_BPM, Resting_BPM, Session_Duration (hours),Calories_Burned, Workout_Type, Fat_Percentage, Water_Intake (liters), Workout_Frequency (days/week), Experience_Level, BMI.

---
## 📊 Model Evaluation Metrics
 * Mean Absolute Error (MAE)
 * Mean Squared Error (MSE)
 * R² Score (Regression Performance)

---
## 🛠 Technologies Used
    🔹 Python 
    🔹 Pandas, NumPy – Data preprocessing
    🔹 Matplotlib, Seaborn – Data visualization
    🔹 Scikit-Learn, XGBoost – Machine Learning models
    🔹 Jupyter Notebook

---
## 🚀 How to Use
   * 1️⃣ Navigate to the Calories-Burnt-Prediction folder.
   * 2️⃣ Open the notebook.ipynb file in Jupyter Notebook.
   * 3️⃣ Run the notebook to train models and predict calories burned.
----
## 📌 Fitness & Health Impact
   * 📈 This model helps fitness enthusiasts, trainers, and health professionals accurately track calorie burn based on user-specific data.

