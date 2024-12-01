# A multiple-linear-regression-model
TASK I: Research Question A1. What factors influence TotalCharge during a hospital stay for a patient? 
A2. Goal of the Data Analysis: The goal of this analysis is to understand the relationships between the dependent variable TotalCharge and independent variables. It is also to identify the factors that influence the total charges patients pay during their hospital stay. The analysis will provide insight into what affects healthcare costs to healthcare administrators.

Part II: Method Justification 


B1. Summarize the four assumptions of a multiple linear regression model: Homogeneity of variance or homoscedasticity: constant variance of the residuals. Multicollinearity: two or more of the predictors correlate strongly with each other. Normality: normal distribution of the error. Linearity: the regression line should represent the points. B2. Describe two benefits of using Python for various phases of the analysis: For this analysis, Python will be used. Python has many libraries and packages needed for analysis and offers greater visualization tools. 


B3. Explain why multiple linear regression an appropriate technique is to use for analyzing the research question summarized in Part I: The research question is investigating factors contributing to TotalCharge. We have one dependent variable, which is TotalCharge, and we are examining multiple independent variables that can potentially influence the total amount patients pay during their hospital stay. Independent variables include 'VitD_levels,' 'Doc_visits,' 'Full_meals_eaten,' 'vitD_supp,' 'Soft_drink,' 'Initial_admin,' 'HighBlood,' 'Stroke,' 'Complication_risk,' 'Overweight,' 'Arthritis,' 'Diabetes,' 'Hyperlipidemia,' 'BackPain,' 'Anxiety,' 'Allergic_rhinitis,' 'Reflux_esophagitis,' 'Asthma,' 'Services,' and 'Initial_days.'


Part III: Data Preparation 
C1. On this analysis the file "medical_data" is used. After importing, the data was explored to identify and address any missing values in each variable. There were no missing values detected in any of the columns. Subsequently, the std() function was used to assess outliers. outliers were found in four variables: TotalCharge, Additional_charges, VitD_levels, and Initial_days. The zscore method was applied to treat outliers in all four columns. Also, categorical variables were transformed into numeric values through dummy variables. For categorical variables with more than two options, such as 'Services,' 'Complication_risk,' and 'Initial_admin,' one-hot encoding was implemented to generate numeric values. Lastly, the following variables are not needed to answer the research question and were removed. 'CaseOrder', 'Customer_id', 'Interaction', 'UID', 'City',
