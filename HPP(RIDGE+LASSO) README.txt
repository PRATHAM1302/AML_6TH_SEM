Predicting House Prices using Ridge and Lasso Regression

This notebook explores the task of predicting house prices in King County, Washington State, USA, using Ridge and Lasso Regression. The dataset used in this notebook consists of historic data of houses sold between May 2014 to May 2015, and was obtained from Kaggle. The aim of this notebook is to build a regression model that can predict the sales of houses in King County with an accuracy of at least 75-80%, and to understand which factors are responsible for higher property value - $650K and above.


Files

kc_house_data.csv: The dataset used in this notebook.


Dependencies

This notebook requires the following Python packages:
pandas
numpy
matplotlib
seaborn
sklearn


Contents

The notebook consists of the following sections:

Data Preparation: This section imports the dataset and performs exploratory data analysis, including data cleaning, feature engineering, and visualizations.

Modeling: This section builds Ridge and Lasso regression models using the cleaned and engineered data, and evaluates their performance on a test dataset.

Model Interpretation: This section examines the coefficients of the Ridge and Lasso regression models to identify which features are most important for predicting house prices.

Results

The final Ridge regression model achieved an accuracy of 78%, while the final Lasso regression model achieved an accuracy of 77%. Both models identified several important features for predicting house prices, including square footage, number of bedrooms and bathrooms, and location.