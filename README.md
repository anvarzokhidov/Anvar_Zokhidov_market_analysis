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
  
### Requirements
- Use Python and a jupyter notebook either locally or on Google Colab (Recommended)

Libraries to be installed and imported (pip install library_name):
- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt
- import scorecardpy as sc
- import statsmodels.api as sm
- from statsmodels.stats.outliers_influence import variance_inflation_factor
- from sklearn.feature_selection import RFECV, SelectFromModel
- from sklearn.linear_model import LogisticRegression
- from sklearn.model_selection import StratifiedKFold, train_test_split, GridSearchCV
- from sklearn.metrics import classification_report, f1_score, roc_auc_score
- from sklearn.preprocessing import StandardScaler, OneHotEncoder
- from sklearn.compose import ColumnTransformer
- from sklearn.pipeline import Pipeline
- from sklearn.metrics import roc_curve, auc, accuracy_score, f1_score, confusion_matrix
- import seaborn as sns
- import joblib
- from sklearn.svm import SVC
- from sklearn.ensemble import RandomForestClassifier
- from xgboost import XGBClassifier
- import torch
- import torch.nn as nn
- from torch.utils.data import Dataset, DataLoader
- import warnings
