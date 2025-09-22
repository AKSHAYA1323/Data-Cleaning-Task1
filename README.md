🧹 Task 1: Data Cleaning & Preprocessing

📌 Objective
The goal of this task is to clean and preprocess raw data (Titanic dataset) so that it can be used effectively for machine learning models.

📊 Dataset
Name: Titanic Dataset
Source: Kaggle Titanic Dataset
Description: Contains passenger details such as Age, Gender, Class, Fare, Embarked Port, and Survival status.

🔧 Steps Performed
1. Import & Explore DatasetLoaded the Titanic dataset using Pandas.Checked shape, data types, and missing values.
2. Handle Missing Values
Filled missing Age values with median.
Filled missing Embarked values with mode.
Dropped Cabin column due to too many missing values.
3. Encode Categorical Variables Converted Sex and Embarked columns into numeric form using One-Hot Encoding.
4. Feature ScalingStandardized Age and Fare columns using StandardScaler to bring them to mean=0 and std=1.
5. Outlier Detection & Removal Used boxplots to visualize outliers in Age and Fare.Applied IQR method to remove extreme values.
6. Save Processed Data Exported cleaned dataset as titanic_cleaned.csv.


📈 Visualizations
Heatmap of missing values.
Boxplots of Fare and Age (before and after outlier removal).
Distribution plots to verify scaling.

🛠 Tools & Libraries Python
Pandas → Data manipulation
NumPy → Numerical operations
Matplotlib & Seaborn → Visualization
Scikit-learn → Feature scaling

🎯 What I Learned
Handling missing values (mean, median, mode, drop).
Encoding categorical features (Label vs One-Hot Encoding).
Standardization vs Normalization.
Outlier detection with boxplots, IQR, and Z-score.
Importance of preprocessing for ML model accuracy.

📂 Repository Structure
📂 Data-Cleaning-Task1
 ├── Task1_Data_Cleaning.ipynb   # Jupyter/Colab Notebook
 ├── titanic_cleaned.csv         # Cleaned dataset
 └── README.md                   # Documentation

