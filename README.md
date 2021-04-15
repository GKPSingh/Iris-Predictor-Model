# Iris-Predictor-Model

#### Predicting class of Iris Flower using machine learning
<img src="https://github.com/GKPSingh/Iris-Predictor-Model/blob/main/Images/iris-flower-garden.jpg" width="900" height="400">

##### Introduction
This notebook is dedicated to the prediction of class of Iris flower based on the different parameters: 

Following Approah will be implemented:

* Problem definition 
* Data
* Evaluation 
* Features 
* Modelling 
* Experimentation

##### 1. Problem Defination
Based on the iris sepal and petal length and width parameters, will it be possible to predict the class if Iris flower.

###### 2. Data Collection
The original data came from the Fisher's data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/machine-learning-databases/iris/

###### 3. Evaluation
After modelling, main motive is to find the category of the Iris Flower

##### 4. Data Features or Data Attributes

Information of different attributes of data is given below:

Create data dictionary
sepal length in cm
sepal width in cm
petal length in cm
petal width in cm
class:
-- Iris Setosa

-- Iris Versicolour

-- Iris Virginica

#### Important Libraries
I imported several libraries for the project:

  + numpy: To work with arrays
  + pandas: To work with csv files and dataframes
  + matplotlib: To create charts
  + seaborn: To create different category charts
  + train_test_split: To split the dataset into training and testing data

#### Approach
1. Data Wrangling

2. Exploratory Data Analysis (EDA) on the data set.

3. For modeling, I have identified 7 models to try:

    I will be using different models to study our data:

      * Logistic Regression
      * SVM- Support Vector Machine
      * KNeighbors
      * Naive Bayes
      * DecisionTreeClassifier
      * RandomForestClassifier
      * GradientBoostingClassifier

4. Test size of Train-Test-Split is set to 20%
