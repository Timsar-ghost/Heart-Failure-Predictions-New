# Heart-Failure-Predictions-New


**1 Introduction:**

Heart Disease is the leading cause of death globally, accounting for 31% of all deaths, with an estimated 17.7 million lives lost each year because of heart disease. 
Cardiovascular Disease could be from heart attacks and strokes and could happen prematurely in people under 70. Since heart failure is a common cardivasdul disease, I try to build a model that predicts heart failure which helps to predict potential heart disease.


**1.2 Data:**

Our data is from Kaggle and It has 918 observations and 12 variables including the response variable named HeartDisease with a value of 0 (normal) or (Heart disease). To explain some of the important variables, could be old peak and ST_slop the feature of exercise electrocardiogram(ECG). The old peak is St depression include by exercise relative to rest and low reading can be a sign of reduced blood flow to the heart muscle. St slop refers to the direction and changes in the St segment of ECG. The upsloping ST segment may be a normal finding in younger individuals who are physically active while a downsloping St can be indicative of coronary artery disease or other cardiac conditions.


**2.2 Categorical varibles**

We first explored the categorical variable, there are much more men than females diagnosed with heart disease  based on our data


Pics 

**2.3 Numerical Varibles**

Correlation between numerical variables is checked and confirmed there is no strong, The box plot of resting blood shows that there is 1 observation with resting blood pressure equal to 0 and we removed this observation, the box plot of cholesterol also indicates there are some 0 values in the column. since it has lots of zero values in our model, we decide d drop them off to not have data leakage, therefore,  it becomes 152 of 172 of them have heart disease.


**3.1 Modeling**

I selected four different kinds of machine learning that help us to figure out to choose a validation for the best model to predict. We approached for classification model method to get high accuracy.

I chose to use five different models for our project including logistic regression, random forest, decision forces, decision trees, and KNN each with its own set of advantages and disadvantages which are outlined in a table for comparison.

**4.1 Logestic Regression**

We applied a full additive logistic model with all explanatory variables, below is the summary, confusion matrix, and ROC curve of the simple additive model.
Moreover, we had a big change to illustrate the regression model with added significant factor and 2-way interaction evaluated on testing using confusion matrix and ROC curve.


**4.2 Random Forest**

I used Random Forest which is an ensemble learning method that combines multiple decision trees, I used the random forest with significant features such as ST_slop, ChestPainType, and old peak, We got different accuracy for AUC 


**4.3 Decision Tree**

We used a Decision tree which is a tree-based model that split the database on the most informative feature, From the decision tree plot we found that ST_slop and ChestPainType were the top two features for this model



**4.4 K_Nearste neightbors**

We used the k-Nearst Neightbos model, which is an imperative method that finds the k-nearest neighbors in the feature space. We analyzed the variable importance plot and found that ST_Slope, ChestPainType, and ExerciseAngina were the most important features of this model as well.


**4.5 Grouping**
Our Grouping clustering model shows different values in variable ranges, Unfrotutly this method was not accurate because the low cholesterol levels have missing information

Based on the results, it could be concluded that the cholesterol variable may not have a significant impact nt of the prediction of heart disease in this data, although we initially considered deleting observations with zero choloersotl values due to the importance of cholesterol 

**Conclusion**

Our study shows a different regression model to predict heart failure. ST_Slop, ChestPainType, and old peak were consistently the most noticeable feature, The logistic regression and k-Nearest neighbors are the best perfidious made according to our scores. Future work in this area need to collect more accurate and complete information about cholesterol level, additionally, more research needs more interaction between cholesterol level and other variable in predicting heart disease.










 
