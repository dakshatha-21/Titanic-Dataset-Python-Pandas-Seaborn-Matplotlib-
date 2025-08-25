# Titanic-Dataset-Python-Pandas-Seaborn-Matplotlib

Titanic Dataset Analysis

**Project Overview**:

This project involves exploratory data analysis (EDA) and visualization of the Titanic dataset to uncover insights about passenger survival patterns. The goal is to understand which factors influenced survival chances using statistics and visual plots.

**Dataset Description**

The Titanic dataset contains data for 891 passengers, including the following key attributes:

PassengerId: Unique identifier for each passenger

Survived: Survival status (0 = No, 1 = Yes)

Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

Name: Passenger name

Sex: Gender of passenger

Age: Age in years

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Passenger fare

Cabin: Cabin number (often missing)

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

**Tools Used**

Python

Pandas (data manipulation)

Matplotlib & Seaborn (data visualization)

Machine Learning 

Jupyter Notebook

**Methodology**

Data Loading and Cleaning

Loaded dataset and examined structure

Handled missing values (age, cabin, embarked)

Descriptive Statistics

Summarized numeric features using .describe()

Examined value counts for categorical variables

**Visual Explorations**

Countplots for survival by gender, class, and embarkation point

Histograms and boxplots for age and fare distributions

Heatmap for correlation matrix between numerical features

Pairplots to observe relationships colored by survival status

**Observations and Insights**

Females had significantly higher survival rates than males

First class passengers survived at higher rates than lower classes

Age distribution showed children had better chances

Higher fares correlated positively with survival

**Conclusions**

Gender and passenger class were the strongest predictors of survival

Socioeconomic status (class, fare) played a major role

Further modeling could include feature engineering for better predictions

**Key Visualizations**

Survival Count by Gender: Highlights female survival advantage

Survival Count by Class: Shows first class survival superiority

Age Distribution by Survival: Displays age influence on survival odds

Correlation Heatmap: Displays relationships among numeric features like age, fare, and family aboard

Pairplots: Visualizes bivariate relationships segmented by survival

**How to Run**

Clone/download the repository

Ensure required libraries are installed (e.g., pip install pandas seaborn matplotlib)

Run the Jupyter notebook or Python scripts for EDA

Review visual outputs and summary statistics




# Titanic Survival Prediction (EDA & Machine Learning)
# 📌 Project Overview

This project explores the Titanic dataset using exploratory data analysis (EDA) and machine learning models to predict passenger survival. The goal was to uncover survival patterns and build a reliable predictive model.

📂 Dataset

Train dataset: Passenger details + survival labels (891 rows)

Test dataset: Passenger details without survival labels (418 rows)

Features include: Pclass, Sex, Age, SibSp, Parch, Fare, Cabin, Embarked

# ⚙️ Methodology

Data Cleaning & Preprocessing

Handled missing values (Age, Embarked, Cabin)

Encoded categorical features (Sex, Embarked)

Dropped irrelevant columns (PassengerId, Name, Ticket, HasCabin)

# Exploratory Data Analysis (EDA)

Countplots: Survival by gender, class, embarkation point

Histograms & boxplots: Age and fare distribution

Correlation heatmap: Relationships between numerical features

Pairplots: Bivariate relationships by survival


# Modeling

Split dataset into training (80%) and validation (20%)

Trained Logistic Regression, Decision Tree, and Random Forest models

Best performance achieved with Random Forest Classifier

Results

Random Forest Validation Accuracy: 84.36%

Predictions generated for the test dataset and saved as submission.csv

# 🔑 Key Insights

Females and 1st-class passengers had significantly higher survival rates

Children had better chances than adults

Higher fares were positively correlated with survival

# 🛠️ Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

# ▶️ How to Run
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Titanic.ipynb



