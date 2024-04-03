### Startup Success Prediction Analysis

**Author: Min Jeong (MJ) Oh**

This repo contains Capstone Project Part 1 from Berkeley Engineering & Berkeley Haas Professional Certificate in Machine Learning and Artificial Intelligence. This initial report and EDA, and more detailed report including the explanation of the data source will be followed in the Capstone Project Part 2.

#### File Navigation
A Jupyter notebook named "Startup Success Prediction.ipynb" contains the code for this analysis. startup_data.csv contains the data used for this analysis.


#### Executive summary
In this project, we aim to predict the success of startups based on various features such as location, funding rounds, funding amounts, and more. We'll utilize machine learning models to identify key factors contributing to startup success.

#### Rationale
Understanding the factors that contribute to startup success can provide valuable insights for investors, entrepreneurs, and policymakers. By predicting the success of startups, stakeholders can make informed decisions to support promising ventures and foster innovation.

#### Research Question
Can we predict the success of a startup based on its location, funding history, and other attributes?

#### Data Sources
The dataset used for this analysis contains information about various startups, including their location, funding history, and other relevant attributes.

#### Methodology
I followed these steps:

Data Cleaning and Preprocessing: Removed unnecessary columns and handled outliers in the 'avg_participants' column.
Exploratory Data Analysis (EDA): Explored the distribution of the target variable, categorical variables, and continuous variables through visualizations.
Feature Engineering: Label encoded categorical variables.
Model Selection and Training: Used three classification models - Logistic Regression, Random Forest, and Support Vector Machine (SVM) for prediction.
Model Evaluation: Evaluated the models based on accuracy scores and classification reports.


#### Results
The predictive model achieved the following accuracies:

Logistic Regression Accuracy: 74.53%
Random Forest Accuracy: 79.80%
SVM Accuracy: 73.68%

Key features contributing to startup success, based on the Random Forest model, include:

- Number of relationships
- Total funding amount in USD
- Age of the last funding year 


#### Next steps
Further analysis can be conducted to:

- Incorporate additional data sources
- Fine-tune the model parameters
- Explore advanced machine learning techniques

#### Outline of project

- Exploratory Data Analysis (EDA) and Visualization
- Data Cleaning and Preprocessing
- Model Selection and Training
- Model Evaluation


##### Contact and Further Information
For questions or additional information, please contact ohmjoh@gmail.com


