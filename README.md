🌌 End-to-End Data Science Pipeline: Light Pollution & Aurora Prediction

An end-to-end data science project that transforms raw citizen science observations into predictive insights for identifying locations with high potential for observing the Aurora Borealis. This project covers the full data lifecycle, including data collection, engineering, statistical analysis, imputation, clustering, data fusion, and supervised machine learning.

The pipeline is built using multi-year Globe at Night light pollution data combined with external solar activity indices, resulting in a complete, analysis-ready dataset and a predictive classification model.

🚀 Project Overview

Problem Statement
Light pollution significantly impacts night-sky visibility. By combining sky darkness measurements with solar activity data, this project aims to identify geographic and temporal conditions that are favorable for aurora observation.

Key Outcomes

Built a reusable data engineering and analytics pipeline

Handled missing data using KNN-based imputation

Discovered hidden patterns using clustering

Fused external solar activity data for predictive modeling

Trained and evaluated a Random Forest classifier

🧩 End-to-End Workflow
1️⃣ Data Collection & Web Scraping 

Programmatically scraped multi-year CSV files from the Globe at Night website

Automated dataset discovery using BeautifulSoup

Created a reproducible ingestion pipeline for raw observational data

Skills: Web scraping, automation, data ingestion

2️⃣ Data Engineering & Feature Preparation

Merged fragmented datasets (2014–2024) into a single DataFrame

Converted categorical fields into numeric and binary features

Engineered time-based and location-based variables

Produced clean, analysis-ready datasets

Skills: Pandas, feature engineering, data cleaning

3️⃣ Statistical Analysis & Geospatial Visualization

Performed descriptive statistics and correlation analysis

Analyzed sky quality metrics across regions, seasons, and years

Built static plots and interactive Folium maps for spatial insight

Skills: Exploratory Data Analysis, visualization, geospatial analytics

4️⃣ Data Imputation & Unsupervised Learning 

Addressed missing SQM readings using K-Nearest Neighbors imputation

Prepared fully numeric feature space for modeling

Applied K-Means clustering to uncover latent observational patterns

Visualized cluster structure using heatmaps and maps

Skills: Data imputation, clustering, unsupervised learning

5️⃣ Data Fusion & Supervised Machine Learning

Integrated external solar activity (Ap index) data

Engineered seasonal features from timestamps

Designed synthetic labels using domain-driven criteria

Trained and evaluated a Random Forest classifier to predict aurora-favorable locations

Skills: Data fusion, supervised learning, model evaluation

🛠 Tools & Technologies

Python

Pandas & NumPy

Scikit-Learn

BeautifulSoup

Folium

Matplotlib & Seaborn

Jupyter Notebook

📊 Results Summary

Improved dataset completeness through KNN imputation

Identified distinct observational clusters using unsupervised learning

Successfully trained a classifier to predict aurora-favorable conditions

Demonstrated the feasibility of combining environmental and solar data for predictive analytics

🔥 Why This Project Matters

This project mirrors real-world data science work by:

Handling messy, incomplete data

Combining multiple data sources

Applying both unsupervised and supervised learning

Emphasizing interpretability and domain awareness

📁 Dataset Source

Globe at Night (Citizen Science Light Pollution Project)
https://globeatnight.org/maps-data/
