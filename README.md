# churn-hotel-xgboost-alibi
An XGBoost model in Python that classifies if a customer will cancel his/her hotel booking or not. I also use counterfactuals guided by prototypes from the Alibi package to explore the minimum changes needed to flip a prediction from canceled to not canceled and vice versa. 

The project 'churn_xgboost_alibi_lennart_wallentin.ipynb' is mainly structured as follows:

(1) Data preparation
    
    (1.1) Data presentation
    (1.2) Handling NA and missing values
    (1.3) Check data types and outliers 
    (1.4) Correlation - Pearson and Cramer’s V 
    (1.5) Avoid unique values
    (1.6) Encoding and create train and test sets		

(2) XGBoost
    
    (2.1) Hyperparamter tuning - Bayesian optimization
    (2.2) Evaluate the model 

(3) Alibi
    
    (3.1) Counterfactuals Guided by Prototypes - in action

The xlsx-file, ‘bayesian_optimization_iterations.xlsx’ contains all the Bayesian optimization iterations. 
