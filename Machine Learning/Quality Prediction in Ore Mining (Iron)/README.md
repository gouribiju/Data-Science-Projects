# ⛏️ Quality Prediction in Ore Mining


## 📌 Overview
This project aims to predict the percentage of silica (impurity) in the iron ore concentrate using real industrial data from a mining process. Accurate prediction of silica content helps in optimizing the beneficiation process, leading to cost reduction and improved product quality.

---
## 🔍 Problem Statement
In the mining industry, the presence of silica in iron ore concentrate is undesirable as it affects the quality of the final product. Predicting the silica content enables engineers to take preemptive actions to reduce impurities, thereby enhancing the efficiency of the mining process.

---
## 📊 Data Preprocessing & Feature Engineering

 * Missing Values Handling:
     *Checked for missing values and ensured data completeness.
 * Feature Engineering:
     * Created new features based on domain knowledge to enhance model performance.
     * Selected important features using correlation analysis and feature importance metrics.
 *Data Resampling:
     * Aggregated sensor data from 20-second intervals to hourly averages to reduce noise and computational load.

---
## 🏆 Machine Learning Models & Performance


|  Model                           |   R² Score (%)  |
|----------------------------------|---------------------------------|
|Linear Regression               | 
|Decision Tree Regression     | 
|Random Forest Regression          | 
|Support Vector Regression (SVR)  | 
|CatBoost Regression           | 
K-Nearest Neighbors (KNN)          | 

---
## 📂 Dataset Details
 * Dataset Name: MiningProcess_Flotation_Plant_Database
 * Source: Kaggle Dataset
 * Columns:  24 attributes including sensor measurements and process parameters.

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
   * 1️⃣ Navigate to the Quality Prediction in Ore Mining Folder.
   * 2️⃣ Open the notebook.ipynb file in Jupyter Notebook.
   * 3️⃣ Run the notebook to train models and predict silica content.
----
## 📌 Industrial Impact
   * 📈This model assists mining engineers in monitoring and controlling the quality of iron ore concentrate, ensuring that the silica impurity remains within acceptable limits to improve overall product quality and process efficiency.




