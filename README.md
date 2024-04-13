# Overview
This project aims to conduct customer segmentation using supervised machine learning techniques, particularly Decision Trees and Random Forests, on a dataset containing vehicle data. The dataset encompasses diverse attributes including selling price, kilometers driven, fuel type, seller type, transmission type, and owner status. Through classification, the goal is to effectively categorize customers into segments based on their characteristics, enabling targeted marketing strategies and personalized customer experiences.
# Project Objectives
# Problem Statements
1. Classification of Customer Data into Segments using Cross-Validation
2. Classification of Customer Data into Segments using Ensemble Methods
3. Determination of an Appropriate Classification Model
4. Identification of Important Features and their Thresholds for Classification
# Data Description
- Source and Size
- Data Source: (https://www.kaggle.com/datasets/kanyianalyst/customer-age-group-segmentation)
- Data Size: 1 MB
- Data Shape: 113037 rows × 12 columns
# Variables
## Categorical Variables
- Nominal Categories: Age_Group, Customer_Gender, Country, Product_Category, cluster
- Ordinal Categories: None
## Non-Categorical Variables 
Customer_Age, Age_Group_NUMBER, Order_Quantity, Unit_Cost, Unit_Price, Profit, Revenue
# Data Analysis
- Descriptive Statistics
- Summary statistics for categorical and non-categorical variables
- Correlation analysis
# Data Pre-Processing
- Missing data treatment
- Encoding categorical variables
- Outlier detection and treatment
- Data transformation and scaling
- Train-test split
# Model Building and Evaluation
- Base Model (Decision Tree)
- Metrics: Accuracy
- Results: Perfect accuracy, efficient training time, moderate memory usage
- Feature Analysis: 
- Relevant feature 
# Comparison Model (Random Forest)
- Metrics: 
- Cross-validation accuracy, confusion matrix
# Results: 
- High accuracy, longer training time compared to Decision Tree
- Feature Analysis: 
- Significant feature 
# Results and Insights
# Model Parameters: 
- Comparison of accuracy and training time between Decision Tree and Random Forest
# Variable Analysis: 
- Relevant features identified by the models
# Managerial Insights: 
- Real-life applications and implications of the classification models
GitHub Repository
The code and documentation for this project can be found in the GitHub repository.
