# House-Price-Prediction

## Project Overview

This project aims to predict house prices based on property features using Machine Learning.
The notebook walks through data cleaning, exploratory analysis, feature engineering, model training, and evaluation.

By the end, we develop a model that can estimate property prices with good accuracy, useful for real estate businesses, property buyers, and sellers.

## Objective

- Perform descriptive and exploratory data analysis using Python. 
- Engineer meaningful features for modeling and segment borrowers by risk levels.
- Build a classification model to accurately predict loan default risk.
- Design a Power BI dashboard for intuitive, interactive, and actionable insight delivery

## Data Overview

- Source: “House Prices: Advanced Regression Techniques”
- Target Variable: Price (continuous)
- Sample Features: Lot area, Year built, Number of bedrooms, Bathrooms, Square footage, Location/neighborhood, Garage size, etc.
    
## Tools & Technologies

- Data Analysis	– Pandas, NumPy, Matplotlib, Seaborn
- ML Modeling	Python – Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
- Data Format	CSV file 


## Machine Learning Model (Python)

- Built a supervised regression model to predict house prices:
- Steps:
   - Data Cleaning & Feature Engineering:Encoded categorical variables, handled missing values, and created features.
- Modeling:
- Model used: DTRegressor

#### Steps followed in the notebook:

- Data Preprocessing
    - Handle missing values
    - Encode categorical features
    - Scale numeric features

- Exploratory Data Analysis (EDA)
   - Price distribution
   - Correlation heatmaps

- Feature vs. target relationships
    - Feature Engineering
    - Derived features like house age, total square footage, etc.

- Model Training
   - Linear Regression (baseline)
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting / XGBoost

- Evaluation Metrics
    - RMSE (Root Mean Squared Error)
    - MAE (Mean Absolute Error)
    - R² Score


#### Result


| Model             | Best Score                              |
| ------------------ | ---------------------------------- |
| linear_regression           | 0.829717                              |
| lasso      | 	0.672900	                             |
| decision_tree  | 0.672900                               |

## Future Enhancements

- Incorporate real-time house prices for scoring via REST APIs.
- Add macroeconomic variables (like inflation).
- Deploy model using Flask + Streamlit + SQL backend

