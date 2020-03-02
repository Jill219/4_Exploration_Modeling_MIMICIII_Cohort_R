# 4 Exploration and Modeling of a MIMIC III Cohort by R  

*05/2019*.  

### Objects:    

  * Request a cohort of heart failure patients from CCU with vital features from the MIMIC III dataset using SQL.   
  * Utilize different methods to predict heart failure mortality in CCU, including logistic regression, SVM, decision tree, random forest and boosting models.   
  * Chosen one favorite model from those predictable models evaluated by confusion matrix, ROC curves and AUC.   
	
### Steps: 

  1. Request a cohort of heart failure patients with ICD9 codes from CCU with vital features from the MIMIC III dataset by SQL (Group). 
  
  2. EDA:    
   * Data cleaning.   
   * Descriptive Statistics information on the data.  
   * Visualizations of the distributions of key variables by the response variable.  
   * visualizations of relationships between variables.  
    
  3. ML:  
   * Split data into train and test sets, impute Na.  
   * Fit and evaluate different models and tune hyperparameters, including logic regression, SVM, a decision tree, random forest and xgboost models.   
   * Plot multiple ROC curves of different models, identify a favorite one.  
