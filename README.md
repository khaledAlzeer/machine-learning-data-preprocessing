📊 Data Preprocessing Tools – Machine Learning Preparation

📖 Project Overview

This project demonstrates essential Data Preprocessing techniques used before training Machine Learning models using Python and Scikit-Learn.

The goal is to prepare raw data for machine learning by applying:

- Handling missing values
- Encoding categorical data
- Splitting dataset into training and test sets
- Feature scaling

These steps ensure the dataset is clean, numerical, and properly formatted for model training.

------------------------------------------------------------

📂 Dataset Description

The dataset contains:

| Column     | Description |
|------------|------------|
| Country    | Categorical independent variable |
| Age        | Numerical independent variable |
| Salary     | Numerical independent variable |
| Purchased  | Dependent variable (target) |

------------------------------------------------------------

⚙️ Preprocessing Steps

1️⃣ Import required libraries (NumPy, Pandas, Matplotlib)  
2️⃣ Load dataset using Pandas  
3️⃣ Handle missing values using SimpleImputer (mean strategy)  
4️⃣ Encode categorical independent variable using OneHotEncoder  
5️⃣ Encode dependent variable using LabelEncoder  
6️⃣ Split dataset into Training and Test sets (80% / 20%)  
7️⃣ Apply Feature Scaling using StandardScaler  
