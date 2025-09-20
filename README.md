#  Movie Rating Prediction

## Overview
This project aims to predict **movie ratings** using machine learning techniques.  
The goal is to build a model that learns from historical data (such as movie attributes and user behavior) to forecast how users would rate a given movie.  
This can help streaming platforms, production houses, and recommendation systems better understand audience preferences.  

---

## Dataset
The dataset contains information about movies and their ratings. Key features include:

- **Rank**: Unique identifier for each movie  
- **Title**: Movie title  
- **Genres**: Categories associated with the movie  
- **UserID**: Unique identifier for each user  
- **Rating**: The rating given by a user (target variable)  
- **Additional Features**: Such as number of directors, number of actors, budget, release year, etc.  

---

## Data Cleaning & Preprocessing
- Removed missing or invalid values  
- Encoded categorical variables (e.g., genres, directors)  
- Standardized numerical features

---

## Modeling
- Applied **Linear Regression, Ridge, Lasso, and Polynomial Regression**  
- Performed **feature scaling** using StandardScaler  
- Used **GridSearchCV** to tune hyperparameters  
- Compared models using **R² score** and **RMSE**  

---

## Results
- Best performing model: **Lasso Regression**  
- Achieved an **R² score of ~0.67** on the test set 
