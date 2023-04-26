Heart Disease Prediction

This code predicts whether a person has heart disease based on various medical and lifestyle factors. It uses various classification models to predict the target variable, which is whether or not a person has heart disease.


Dataset

The dataset used in this code is heartDisease.csv. It contains data on 303 patients and 14 features including age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, thal, and target. The target variable is binary, with 1 indicating the presence of heart disease and 0 indicating the absence of heart disease.


Workflow

Import necessary libraries


Load the dataset

Explore the dataset using head(), describe(), and info() methods to get an idea of the data
Check for missing values using the isnull() and sum() methods
Visualize the data using countplot() and pairplot() methods from seaborn library
Split the data into features and target
Split the data into training and testing sets using train_test_split() method from sklearn library
Scale the data using StandardScaler() method from sklearn library
Fit the data to various classification models including LogisticRegression(), KNeighborsClassifier(), SVC(), GaussianNB(), DecisionTreeClassifier(), RandomForestClassifier(), and xgb.XGBClassifier()
Calculate the accuracy of each model on the test set using score() method from sklearn library
Visualize the accuracy results using bar() method from matplotlib library


Conclusion

The model with the highest accuracy is chosen as the best model to predict whether a person has heart disease or not. This code can be used to predict the likelihood of a patient having heart disease and can be used in clinical settings to help healthcare professionals make more informed decisions.
