# HealthPredict--Advanced-Healthcare-Cost-Analysis-


The project titled "Analysis and Prediction of Health Care Costly Customers" conducted by (Aditi Pala, Indra Ariunbold, Rujuta Mirajkar, Jaineel Parmar, Rithvik Segu) for IST 687 – Introduction to Data Science can be summarized as follows:

The main objective of the project was to offer actionable insights and estimate individuals (clients) who would incur expensive healthcare costs. The dataset used contained healthcare expenses from an HMO (Health Management Organization).

# Introduction: 
The project utilized R packages such as tidyverse, caret, ggplot2, fastDummies, ggmap, and shiny. Data importation involved reading a CSV file via URL to access structured data.

Determining Threshold for Expensive Variable: A criterion based on location and location type was established to segregate expensive healthcare costs. The average cost per person based on location was used as the threshold.

Exploratory Data Analysis: Graphical analysis was conducted on numerical and categorical variables, exploring histograms, bar plots, box plots, and the connection between variables and healthcare costs.

Geographical Analysis: Location information was used to illustrate average healthcare costs per person on maps, showing variations across different states.

Building Predictive Model: Categorical variables were converted into dummy variables, and the data was split into training and testing subsets. Four models were trained: K-nearest neighbors, Support Vector Machines, Logistic Regression, and Neural Network. The Neural Network model was selected as the best for making predictions.

# Conclusion: 
Smoking, exercise, age, and BMI were identified as the most important variables influencing healthcare costs. Recommendations included identifying smokers and promoting smoking cessation programs, encouraging exercise among individuals with high BMI and older age, and emphasizing the importance of yearly check-ups for early detection of health problems.

The project provided insights into predicting healthcare costs and offered recommendations for targeted interventions to reduce healthcare expenses.
