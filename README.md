# 🛣️ Road Accident Risk Prediction

This project aims to predict **the risk of road accidents** based on various environmental, traffic, and temporal factors.  
It was built as part of a Kaggle competition focused on improving road safety insights through machine learning.

## 📘 Project Overview

The goal is to build a predictive model that estimates the **likelihood of a road accident** under given conditions.  
By analyzing features like weather, time, location, and road type, we aim to help authorities and urban planners take proactive measures to reduce accidents.


## 🧠 Key Steps

1. **Data Preprocessing**
   - Handled missing values, encoded categorical features, and normalized continuous ones.
   - Removed or engineered features to enhance model signal.

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions, correlations, and outliers.
   - Identified high-risk patterns across different regions and times.

3. **Feature Engineering**
   - Created new features like 'curve_lane_risk', 
                 'extreme_risk','speed_lanes_risk',
                 'sharp_curve_high_speed'.
   - Removed weakly correlated or redundant features.

4. **Modeling**
   - Started with **CatBoost**, which performed best initially.
   - Experimented with **XGBoost** and **LightGBM** for comparison.
   - Used cross-validation to validate results locally before Kaggle submission.

5. **Evaluation**
   - Evaluated using competition metric- Root Mean Square Error (RMSE).
   - Final model tuned and submitted to Kaggle leaderboard.

