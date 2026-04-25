Nepal Macroeconomic Analysis

A Machine Learning-based system that predicts economic distress in Nepal using macroeconomic indicators, deployed as a live interactive dashboard.

About the Project
This project builds an end-to-end Machine Learning pipeline that:

Collects macroeconomic data for Nepal from the World Bank, IMF, and Nepal Rastra Bank
Engineers features tailored to Nepal's unique economic structure (remittances, India linkage, forex vulnerability)
Trains and compares multiple ML models (Logistic Regression, Random Forest, XGBoost, LSTM)
Outputs a recession probability score updated annually
Displays everything on a live Streamlit dashboard

Recreate from this file:
bashconda env create -f environment.yml
conda activate nepal-recession
