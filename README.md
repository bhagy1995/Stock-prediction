# Stock-prediction

The scope of this project is to predict multi asset returns in the stock market. The objective of the 
project was to explore many different machine and deep learning models to determine which 
model would best to accurately predict multi-asset returns in the stock market. In this project we 
used both regression and classification algorithms. The assets selected for this investigation 
project are Apple, Microsoft, and IBM.

Feature engineering was the first step of the data preparation process. To better teach our model the underlying patterns of the stock market, we introduced 9 technical indicators.

The second step in the data preparation process is feature selection. We first wanted to 
understand the relationship between the features and the target variable. To understand the 
APS1052: Artificial Intelligence in Finance Final Project Presentation Script 
relationship between features, we used seaborn’s heatmap to display the correlation each 
feature has with one another. We did this because we wanted to remove features with high 
collinearity since these features would only introduce redundant information to the model and 
increase the model’s complexity.

The next step in the feature selection process was to apply Recursive Feature Elimination (RFE) 
to our dataset, to obtain the optimal number of features.

The last step in the data preparation process was feature tuning (i.e., feature smoothing). Before 
we committed to smoothening our data, we first checked to see if our data contains any trends, 
seasonal patterns, or noise.

A number of regression and classfication models were implemented. Compounded Annual Growth 
Rate (CAGR). It is a good measure to evaluate multiple stocks against each other and how they 
perform over time. However, it does not account for the investment risks. For large-scale companies such as Microsoft and IBM, CAGR of 5-12% is good. Light GBM and Stacking regressors 
indicate high test CAGR scores.

