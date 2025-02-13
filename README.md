# **SONAR Rock vs Mine Prediction Project**

The provided project aims to predict whether a given object is a rock or a mine based on its sonar signal data.

Here is a quick summary:

1. Data Collection and Preprocessing:
*   The dataset is loaded into a pandas DataFrame from a CSV file.
*   The dataset consists of sonar signals with 60 features, and each instance is labeled either "R" (rock) or "M" (mine).

2. Exploratory Data Analysis:

* Basic statistical measures of the data are explored.
* The dataset is checked for the number of instances and distribution of the classes.
3. Data Preparation:

* Features (X) and labels (Y) are separated.
* Labels are encoded from categorical ("R" and "M") to numerical values (1 and 0, respectively) using LabelEncoder.
4. Data Splitting:

* The data is split into training and test sets using train_test_split, with 10% of the data reserved for testing.
5. Model Training:

* A Logistic Regression model is trained using the training data.
6. Model Evaluation:

* The accuracy of the model is evaluated on both training and test data using accuracy_score.
7. Predictive System:

* A function predictive_system is created to predict if a new object is a rock or a mine based on the trained model.
An example input is provided to demonstrate the prediction.
