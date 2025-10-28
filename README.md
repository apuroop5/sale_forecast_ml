# sale_forecast_ml
This project predicts future product sales using historical data. It includes data cleaning, trend analysis, and feature engineering, followed by building and comparing three models — Linear Regression, Random Forest, and Gradient Boosting — to forecast sales and support data-driven business decisions.
This project focuses on analyzing and forecasting product sales using historical data.
The goal is to uncover key patterns, understand demand behavior, and predict future sales using multiple machine learning models.
The notebook demonstrates the complete data science workflow — from data preprocessing and exploratory analysis to feature engineering and model training.
The project uses two main CSV files:
1)target_ts.csv – Contains time-series sales data with item-wise quantities.
2)related_ts.csv – Includes related business features such as item, organization, date, and value.
Both datasets are merged and transformed to create a structured format suitable for forecasting analysis.

Data Preparation:
Loaded and merged datasets using pandas and Converted date columns and handled missing values , Created new features like year, month, and lag for time-based analysis.

Exploratory Data Analysis (EDA):
Visualized trends using matplotlib and seaborn,Compared average sales by items and organizations,Studied correlations between numerical and categorical variables

Feature Engineering:
Encoded categorical variables (item, org) and Created lag features to capture historical dependencies , Generated correlation heatmaps for feature selection

Model Building and Forecasting:
Implemented and compared the performance of three regression models:
Linear Regression – Baseline model for simple trend estimation
Gradient Boosting Regressor – Boosted ensemble model that improves prediction accuracy through iterative learning
Random Forest Regressor – Captures complex non-linear relationships
Each model was trained and evaluated on sales quantity to predict future demand.

Tools & Technologies:
Python
Pandas, NumPy – Data handling and preprocessing
Matplotlib, Seaborn – Data visualization
Scikit-learn – Machine learning models and evaluation
