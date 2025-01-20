# Salary Prediction with Machine Learning

## 📄 Project Overview

This project aims to predict the salaries of baseball players based on their career statistics from the 1986-1987 season using machine learning techniques. The dataset includes various performance metrics such as hits, home runs, and career achievements to develop an accurate predictive model.

## 📊 Dataset Description

The dataset consists of baseball player statistics and salary information, with features including:

- **AtBat**: Number of times at bat during the 1986 season.
- **Hits**: Number of successful hits in the 1986 season.
- **HmRun**: Home runs scored in the 1986 season.
- **Runs**: Runs scored by the player in the 1986 season.
- **RBI**: Runs batted in during the 1986 season.
- **Walks**: Number of walks in the 1986 season.
- **Years**: Number of years played in the major league.
- **Salary**: Player's salary (target variable).
- **League, Division, NewLeague**: Categorical features representing the player's league and division.

## ⚙️ Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Summary statistics and visualizations of key features.  
   - Handling missing values and detecting outliers.  
   - Correlation analysis to identify relationships between features.

2. **Data Preprocessing**  
   - Handling missing values using KNN imputation.  
   - Outlier detection and treatment.  
   - Feature scaling with `RobustScaler`.  
   - Encoding categorical variables using one-hot encoding.

3. **Feature Engineering**  
   - Derived new features such as hit success rate and career-based performance metrics.  
   - Created ratio-based and interaction features to enhance model performance.

4. **Model Development**  
   - Implemented multiple regression models including:  
     - **Linear Regression**  
     - **K-Nearest Neighbors (KNN) Regression**  
   - Model evaluation using RMSE and R² score.

## 🏆 Model Performance

The performance of the models is evaluated using Root Mean Squared Error (RMSE) and R² score:

- **Linear Regression Results:**  
  - Training RMSE: `227.42`  
  - Training R² Score: `0.735`  
  - Test RMSE: `207.32`  
  - Test R² Score: `0.731`  

## 📦 Technologies Used

- **Programming Language:** Python  
- **Libraries:**  
  - `pandas` – Data manipulation and analysis  
  - `numpy` – Numerical computations  
  - `scikit-learn` – Machine learning algorithms  
  - `seaborn` and `matplotlib` – Data visualization 
