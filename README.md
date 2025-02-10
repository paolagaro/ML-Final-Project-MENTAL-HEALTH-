# ML-Final-Project-MENTAL-HEALTH-
Mental Health data set to make a model to predict growing stress. 
We will explore two different types of machine learning algorithms to making predictions about increasing occupation-based stress to identify the model one best fits our data for prediction, the model that we going to be using will be Decision Tree Classifier model and Gradient Boosting Classifier model

The preprocessing:
In order to have a better understanding of my data, I used the functions ".head()",".info()" and ".shape()" then I did a verification of the missing datas, outliers and null values, on self_employed column there were a good number of null values ​​so I proceeded to eliminate them and also the duplicate values. using the '.drop_duplicates()' and '.dropna()' function.

To Decision Tree Classifier model I Create a visualizations to explore patterns, distributions, and relationships in the features of interest to the model. I
use "LabelEncoder()" function to convert the categorical data to numerical data and get a good functioning of the model.

To prepare the model 1)I started splitting, 2) Training and Testing Sets the data 3)training the Decision Tree Model, 4)model evaluated 5)prediction.I used the train model to predict Growing_Stress for the test data and finished with a visualization using correlation to see the relationship between Growing_Stress and Occupations. 

I repeat the same process for Gradient Boosting Classifier and just replaced the Decision Tree Classifier model with Gradient Boosting Classifier model. 
