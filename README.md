# 2020MachineLearnigTraining
Machine Learning Training 
Steps:
1. Business Understanding
2. Data preprocessing (Feature Engineering )
3. Feature Selection
4. Model Building
5. Model Evaluation
6. Deployment 
7. Monitoring the application on live data

###============================================================
## Feature Engineering 
> https://feature-engine.readthedocs.io/en/latest/

> https://www.trainindata.com/all-posts/categories/english

###============================================================

## Feature Selection

1. Filter Methods
  a. Constant - same data in features.
  b. Quasi constant - very less data for the rare categories < 0.1%
  c. Duplicated feature- After applying encoding techniques(Categorical columns)
  d. Correlation - 2 Feature are highly correlated > 85%, we can remove one feature
  e. Statistical Measures -(Fisher score| Chi-Square|Metrics(ROC-AUC))

2. Wrapper Methods (Computationally expensive)(Lasso| Ridge|ElasticNet)
  a. Step forward selection
  b. step backward selection
  c. Exhaustive selection

3. Embedded Methods
  a. Tree based models(DT| RF | GBM)
