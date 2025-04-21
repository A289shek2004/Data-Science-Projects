**🍽️ Food Waste Management Analysis**
A data-driven project to analyze and predict global food waste patterns using Exploratory Data Analysis (EDA) and Machine Learning models.

📌 Problem Statement
Food waste is a critical global issue contributing to environmental degradation, resource depletion, and economic loss. This project addresses the challenge of analyzing and predicting food waste across various sectors (households, retail, and food services) and proposing actionable insights for sustainable food management.

🎯 Objectives
Analyze global food waste trends by sector and region.

Explore key factors influencing food waste using statistical techniques.

Predict future food waste using machine learning models.

Provide insights for policymakers, businesses, and households to reduce waste.

Build a robust data visualization and modeling pipeline.

📊 Dataset Overview
The dataset includes country-wise food waste estimates across:

Households

Retail

Food Services

It covers both absolute values (tonnes/year) and per capita metrics (kg/capita/year), along with regional identifiers.

🧪 Methodology
🔧 Data Preprocessing
Missing value treatment using mean/mode imputation.

Categorical encoding for country names.

Feature scaling using MinMaxScaler.

📈 Exploratory Data Analysis (EDA)
Summary statistics and distributions.

Visual trends across regions and sectors.

Correlation heatmaps and pair plots.

🔍 Outlier Detection
Used Z-Score and Boxplots to detect outliers.

Handled using Winsorization and Log Transformation.

🔬 Machine Learning Models
Two models were implemented:


Model	MAE	MSE	RMSE	R² Score
Linear Regression	9.91	2.35	4.85	1.0
Random Forest Regressor	3.53	58.32	7.63	0.87
✅ Linear Regression showed perfect fitting.
✅ Random Forest offered good flexibility for non-linearity.

🚀 Deployment
Flask API built for real-time food waste prediction.

Deployed on cloud infrastructure for accessibility.

💡 Key Insights
Households are the largest contributor to food waste.

High correlation exists between household, retail, and food service waste.

Machine Learning models can reliably predict food waste and support decision-making.

📌 Recommendations
Governments and businesses should focus on household waste reduction.

Implement real-time ML tracking systems for supply chain optimization.

Develop awareness programs to reduce food waste at the consumer level.

🔭 Future Scope
Time series forecasting for seasonal/annual waste trends.

Policy simulation to measure impact on waste reduction.

Deep learning-based models for enhanced prediction accuracy.

📚 References
UNEP Food Waste Index Report (2021)

FAO SDG Data Portal

IEEE - Predictive Models for Food Waste

👨‍🎓 Project Info
Student Name: Abhishek Kumar Gupta

College: Shree LR Tiwary Degree College

Tools & Technologies: Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Flask, Jupyter Notebook

