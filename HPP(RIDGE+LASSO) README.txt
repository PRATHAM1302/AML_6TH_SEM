Regression Analysis of King County Housing Data


Introduction

This code uses Ridge and Lasso regression models to analyze King County Housing data. The data set contains information about houses sold in King County, WA between May 2014 and May 2015.


Libraries

This code uses the following libraries:

pandas: For data manipulation and analysis.
numpy: For scientific computing in Python.
seaborn: For data visualization.
sklearn: For machine learning modeling and evaluation.


Loading the Data

The King County Housing dataset is loaded using pandas. It is stored in a pandas DataFrame called df.


Preprocessing the Data

The features and target variable are defined. The date feature is dropped, as it is not useful for analysis. Missing values are checked for and no missing values are found. Outliers are checked for using a boxplot. Categorical variables are checked for using the dtypes attribute.


Splitting and Scaling the Data

The data is split into training and test sets using train_test_split. The data is scaled using the StandardScaler from the sklearn library.


Building the Models

Both Ridge and Lasso regression models are fit using the training data.


Evaluating Model Performance

The performance of both models is evaluated using the test set. The mean squared error and R-squared score are calculated for each model. The R-squared score is multiplied by 100 to obtain the accuracy of the models. The results are stored in a pandas DataFrame.


Results

The results are sorted by accuracy in descending order and displayed in a table. The table includes the model name, accuracy score, and model number.
