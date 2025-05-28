# 🌾 Crop Yield Estimator

This project is a machine learning-based tool designed to estimate crop yields based on climatic and agricultural features. By leveraging regression techniques, it provides insights into how various factors influence yield, helping stakeholders make informed agricultural decisions.

### 📌 Project Overview 
Goal: Predict crop yield (tonnes per hectare) using key climatic and environmental features.

Approach: Exploratory data analysis → Feature engineering → Model training and evaluation.

Tools & Libraries:

Python (Jupyter Notebook)

pandas, numpy, matplotlib, seaborn, geopandas, plotly

scikit-learn

### 📊 Features Used
The dataset includes the following predictor variables:

EVI	LST	NDVI latitude	longitude Temperature	Rainfall	EVI_NDVI_ratio	Vegetation_index

Target variable:

Crop Yield (tonnes/ha)

### 🚀 Workflow
Data Loading & Preprocessing

Cleaned and handled missing data

Encoded categorical variables (e.g., Crop Type, Soil Type)

Exploratory Data Analysis

Visualized feature distributions

Assessed correlations and feature importance

Modeling: Random Forest


### 📈 Results

=== Model Performance ===
Training R²: 0.8873
Testing R²: 0.6800
Training RMSE: 8436.78
Testing RMSE: 14763.28
Cross-validation R² (mean ± std): -0.0594 ± 0.9754

Cross-Validation R² Scores: [-1.993001    0.54509743  0.6637972   0.55528818 -0.09597239]
Mean CV R² Score: -0.0650

Overall Model Performance:
MSE: 100534251.71
RMSE: 10026.68
R²: 0.8434
Model Accuracy: 87.76%

Total Importance of Climate Variables: 0.4214 (42.14%)


### 📌 Use Cases

Agricultural planning and policy-making

Precision farming and yield optimization

Insurance and risk assessment

Research and academic studies in agro-informatics


### ✅ Future Improvements

Integrate geospatial data (e.g., NDVI, satellite imagery)

Deploy as a web-based prediction tool (e.g., Streamlit or Flask)

Incorporate time-series data and trends

Extend model to predict yield across multiple years or regions


### 📜 License

This project is open-source under the MIT License.
