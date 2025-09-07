# Electric-Vehicle-Sales-by-State-in-India-Analysis
ElectroTrends India: EV Sales Analysis & Forecasting

📊 Project Overview

ElectroTrends India analyzes and forecasts Electric Vehicle (EV) sales across India using historical sales data. The project uncovers state-wise trends, vehicle-type performance, seasonal patterns, and builds predictive models to forecast future EV sales.

This project helps businesses, policymakers, and EV enthusiasts understand and predict the growth of the Indian EV market.

Example visualization of EV sales trends

🗂 Dataset Column Description Year Year of sale Month_Name Month of sale Date Full date of sale State Indian state or union territory Vehicle_Class Class of vehicle (2W, 3W, 4W, Bus) Vehicle_Category Category (Personal, Shared, Commercial) Vehicle_Type Specific type of vehicle EV_Sales_Quantity Number of EVs sold Month, Day, DayOfWeek, Quarter, Is_Weekend, WeekOfYear Derived time features

Source: GitHub CSV

🎯 Project Objectives

Explore EV sales trends by year, month, state, and vehicle type.

Build regression models to predict EV sales quantities.

Evaluate models using RMSE, MAE, and R² metrics.

Highlight top-performing states, vehicle categories, and seasonal trends.

Visualize trends and residual analysis with intuitive plots.

🛠 Technologies Used

Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Environment: Jupyter Notebook

Modeling: Linear Regression (with potential Random Forest/XGBoost)

Visualization: Trend analysis, heatmaps, bar charts, line plots

🧩 Workflow

Data Loading & Inspection – Check data types, missing values, summary stats.

Data Preprocessing – Handle missing values, encode categorical features, scale numeric features.

Feature Engineering – Extract time-based features (Quarter, WeekOfYear, Is_Weekend).

Exploratory Data Analysis (EDA) – Yearly, monthly, state-wise, vehicle-wise trends.

Model Building – Linear Regression pipeline with scikit-learn.

Model Evaluation – Metrics: RMSE, MAE, R²; residual analysis & feature importance.

Visualization – Actual vs predicted EV sales, state-wise & vehicle-wise trends.

📈 Insights

Top-selling States: Identify leaders in EV adoption.

Vehicle Trends: 2-wheelers dominate sales, followed by 4-wheelers & buses.

Seasonal Patterns: Highlighted monthly & weekly trends.

Prediction Accuracy: Linear Regression captures trends reasonably; non-linear models can improve forecasts.

Business Impact: Supports EV market strategy and policy decisions.
