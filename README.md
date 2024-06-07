# Bank Loan Classification
This project predicts customer loan approval using machine learning models, with data from CIBIL and Bank of Baroda.

<h2> Installation </h2> 

<h3> Install the required libraries </h3> 

- numpy 
- pandas 
- matplotlib 
- scikit-learn 
- scipy 
- statsmodels 
- xgboost 
- flask

# Data Description

- The project uses two datasets:

1. case_study1.xlsx (CIBIL)
2. case_study2.xlsx (Bank of Baroda)

# Data Preprocessing
- Load the datasets.
- Remove missing values and irrelevant columns.
- Merge the datasets on PROSPECTID.
- Feature Selection
- Perform chi-square tests for categorical features.
- Calculate VIF for numerical features to remove multicollinearity.
- Use ANOVA tests for feature selection.
- Model Training

<h4> Train and evaluate three models: </h4>

- Random Forest Classifier
- XGBoost Classifier
- Decision Tree Classifier

<h4> Model Evaluation </h4> 

- Evaluate models using accuracy, precision, recall, and F1 score.

<h4> Hyperparameter Tuning </h4> 

- Use GridSearchCV to tune the hyperparameters of the XGBoost model.

<h4> Deployment </h4> 

- Deploy the final model using Flask for bank professionals to assess loan applications.
