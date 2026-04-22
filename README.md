# Anvar_Zokhidov_market_analysis
# Census Income & Market Segmentation Analysis

### Project Overview
This project uses U.S. Census Bureau data to predict high and low income earners ($>50k and $<50k) and segment the population for marketing purposes. 

### Key Features
- **Classification:** Population-weighted Logistic Regression optimized for ROC-AUC and Gini (Other algorithms included as well).
- **Segmentation:** K-Means clustering ($K=5$) visualized via PCA, UMAP and t-SNE.
- **Business Impact:** Built a classifier and udentified 3 primary life-stage segments representing 342M citizens for targeted retail marketing.

### Files in this Repository
- `Anvar_Zokhidov_Market_Analysis.ipynb`: Full technical implementation and data cleaning.
- `Anvar_Zokhidov_report_market_analysis.pdf`: Executive report with business insights and strategic recommendations.
- `requirements.txt`: Environment dependencies.

### Results
- **Model AUC:** [0.93]
- **Primary Target:** Segment 1 (Main Workforce), representing 51% of the population with the highest income probability.
