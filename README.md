# Anvar_Zokhidov_market_analysis
# Census Income & Market Segmentation Analysis

### Project Overview
This project uses U.S. Census Bureau data to predict high and low income earners (more than 50k and less than 50k) and segment the population for marketing purposes. 

### Key Features
- **Classification:** Population-weighted Logistic Regression optimized for ROC-AUC and Gini (Other algorithms included as well).
- **Segmentation:** K-Means clustering ($K=3$) visualized via PCA, UMAP and t-SNE.
- **Business Impact:** Built a classifier and udentified 3 primary life-stage segments representing 347M citizens for targeted retail marketing.

### Files in this Repository
- `Anvar_Zokhidov_Market_Analysis.ipynb`: Code
  1. Code for training and evaluating classification model.
  2. Code for generating segmentation model.
     (both are in the notebook) 
- `Anvar_Zokhidov_report_market_analysis.pdf`: Executive report with business insights and strategic recommendations.
- `requirements.txt`: Environment dependencies.

### Results
- **Model AUC:** [0.93]
- **Primary Target:** Segment 1 (Main Workforce), representing 51% of the population with the highest income probability.
  
### Requirements (Easy to use Python and jupyter notebook on Google Colab)
- pandas
- numpy
- matplotlib
- scorecardpy
- statsmodels
- scikit-learn
- seaborn
- joblib
- xgboost
- torch
- umap-learn

### Installation
To run this notebook, install the dependencies using:
`pip install -r requirements.txt`
