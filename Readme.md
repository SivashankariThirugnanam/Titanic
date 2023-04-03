# TITANIC PROJECT

The Titanic dataset is a well-known dataset in the field of data analysis and machine learning. It contains information about the passengers who were aboard the Titanic during its maiden voyage, which famously sank in 1912. The dataset includes details about each passenger's age, gender, class of ticket, fare, and whether or not they survived the sinking.

The Titanic dataset is often used as a training set for machine learning models because it provides a real-world example of a classification problem. The goal is to predict whether a passenger survived or not based on the available data.

The dataset is a popular choice for data analysis and machine learning projects because it is relatively small and easy to understand, yet still has enough complexity to be interesting. Additionally, it provides a glimpse into the social and economic factors that influenced the survival rates of the passengers aboard the Titanic.


# Imported Libraries

#for data visualization library
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns

#for mathemaical operations
import numpy as np

#for dataframe manipulations
import pandas as pd

#for model building
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.metrics import confusion_matrix
 

# Overview Analysis

#EDA is performed.
#Descriptive statistics
#Columns Exploring

# Model building 

#Logistic Regression
#DecisionTreeClassifier
#RandomForestClassifier
#Pipeline Creation
#Pipeline without PCA

# Conclusion

In conclusion, the Titanic dataset provides valuable insight into the tragic event that claimed the lives of passengers and crew members aboard the ill-fated ship.Through data analysis, we can understand the demographics of those onboard, the factors that contributed to the sinking, and the survival rate of different groups. This dataset serves as a reminder of the importance of safety measures and caution when traveling, especially in dangerous situations. Furthermore, it demonstrates the potential of data analysis to uncover patterns and correlations in historical events.

Through descriptive statistics we cleaned the dataset. We predict the various model builing to get best accuracy, we can see that without using dimensionality reduction we are able to get better score for our model.We conclude that,

Classifier with best accuracy:Decision Tree-0.79.




