Introduction:

This project aims to predict whether a patient should be diagnosed with heart disease or not based on various features such as age, sex, chest pain type, blood pressure, cholesterol level, etc. The dataset used in this project contains 303 instances of patients with 14 attributes.

Libraries used:

Pandas: for data manipulation and analysis
NumPy: for numerical operations
Matplotlib: for data visualization
Seaborn: for statistical data visualization
Scikit-learn: for machine learning models and preprocessing
Data exploration:

Loaded the dataset using pandas and explored the first few rows, summary statistics and data types.
Checked for missing values and found none.
Visualized the target variable distribution and pair plots of various features.
Data preprocessing:

Split the data into features and target variables.
Split the data into training and testing sets with a test size of 20% and a random state of 42.
Scaled the data using StandardScaler.
Model training and evaluation:

Trained the data on various classification models such as Logistic Regression, Decision Tree, and Random Forest.
Evaluated the accuracy of each model on the test set.
Plotted a bar graph of the accuracies of each model.
Conclusion:

The Random Forest classifier performed the best with an accuracy of 88%.
The model can be used to predict whether a patient has heart disease or not based on their vitals and symptoms.



