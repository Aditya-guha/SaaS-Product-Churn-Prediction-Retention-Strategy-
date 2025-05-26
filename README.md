# SaaS Product Churn Prediction & Retention Strategy
This repository contains a full machine learning and business analysis pipeline to predict customer churn for a B2B SaaS product, identify key churn drivers, and develop actionable retention strategies.

We used Python (pandas, scikit-learn, seaborn, matplotlib) on a synthetic dataset of 100,000 SaaS customers and packaged the work across notebooks for reproducibility and clarity.

## Repository Structure
/saas-churn-prediction
├── Large_SaaS_Churn_Dummy_Data__100K_rows_.csv   # Synthetic SaaS churn dataset (100k records)
├── DV_using_python.ipynb                         # Data visualization: churn trends, patterns
├── SaaS_retention.ipynb                          # Retention strategy, churn modeling notebook
├── requirements.txt                              # Python dependencies
└── README.md                                     # Project overview and instructions

## Project Overview
Built and trained a churn prediction model (Random Forest Classifier)
Identified key churn drivers: plan type, tenure, support interactions, feature usage
Created data visualizations for the Customer Success team
Proposed a retention dashboard and early-warning system for at-risk customers


## Key Results
Metric	Result
Churn prediction accuracy	~75% (update with your result)
Top churn drivers identified	Plan type, tenure, support tickets, feature usage
Retention improvement potential	~17% lift from integrating early churn signals
