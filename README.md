# Heart-Failure-Predictions-New
**1 Introduction:**

Heart Disease is the leading cause of death globally, accounting for 31% of all deaths, with an estimated 17.7 million lives lost each year because of heart disease. 
Cardiovascular Disease could be from heart attacks and strokes and could happen prematurely in people under 70. Since heart failure is a common cardivasdul disease, I try to build a model that predicts heart failure which helps to predict potential heart disease.


**1.2 Data:**

Our data is from Kaggle and It hast 918 observation and 12 varible including the response varible named HeartDisease with a value of 0 (noraml) or (Heart Diseas).
To explain some of the important variable, could be old peak and ST_slop are the feature of excerise electrocardiogram(ECG). Oldpeak is St depression include by excrise relative to rest and low eadinfg can be sing of resduce blood flow to the heart muscle. St slop refers to the disrection adn change in the St segment ofd ECG. The upslcing ST segment may be a normal fininf in younger individiuals who are physiocally active while a downslopingh St can be indicative of cornory arter diseas or other cardiac conditioin.

**2.2 Categorical varibles**

We first explored the categorical varibale, there are much more man than female  in the data in general and also more mna in the heart diease. 


Pics 

**2.3 Numerical Varibles**

correlation between numerical varible are check and conifrmed there no strong , The box plot of resting blood lplease show that there is 1 obsetvation with resting blood pressure equal to 0 and we removed this observation, the bos plot of chlosteol alos indivcate there some 0 values in the column. scinede it is wudel knowe and a lot of many people with 0 cholosterol level have hear diseease, the it tured out 152 of 172 of them have heart dise3as, therfore we got lots of missing zero in cholerteol vaible.



**3.1 Modeling**

I selected four differnt kind of machin leanign that help u sto figure out and choosuibng and validation the best model for prediction, could be complecity, interpretabliy 
and avalibile data nad our uise caarse requirees a clssification model with higth acfcurvaty and interpretablity,


I chose to use five dofferent model for out progect inclihding logistiv rtegression, random forest, decisionn fores, decision treem, and KNN each with their own set of advantage and disadvantage whith atre outline in a table for comparisino.

**4.1 Logestic Regression**

We applierd a full additive logestic model with all explantory varible, below is the summry, confuision m,ateric and ROC curve of the simple adfitive model.
Moreover, we had a big chanfe to iluustrea teh regression model with added significatn factor and 2 way interaction evalued on testing using confusion matrix and ROC curve.




**4.2 Random Forest**

I used Random Forest which is an enesemble learning method that combine multonle decsioin trees, I used the random forest with significant feature such as ST_slop, ChestPainType, and oldpeak, We got differen accuracy for AUC 



**4.3 Decision Tree**

We used Decisin tree wehich is a tree basd model that split the data base on the most information feature, From the secision tree plot we found that ST_slop and ChestPainType were the top two feature for this model



**4.4 K_Nearste neightbors**

We udes the k-Nearst Neightbos model, which is a non param,ertiv mthod that find thge k nearst neighbos in the feature space, we could analyzed the varibel oklot and that founf the ST_slop for the chest paiin Type amnd exercsei anginea were the most important feature for this model as well.



**4.5 Grouping**
Our Grouping clustering model show differtnt vale into variable rangeds, Unfrotutly this method was not accurate becuse of the low cholorsterl levels and miussing information

Based on the results, it could be conclude that the cholestrel variable may not jave signigficanr impn nt of the prediction of heart disease in this data, althought we initially considede deleting observation with zero choloersotl valuies due to the imporantace of cholostrerl 


**Conclusion**

Our studfy shows shows dfiffer4ent regression model to predict heart failure. ST_Slop, ChestPainType, and oldpeak were conistently the most noticdble feature, The logisitc regression and k-Nearest neighborss are the best perfrmioub moide accornidn to our scores. Future work in this area need collectong more accurate and compelet information about cholestrol level, additionaly, more research need more interaction betweeen choesterl level and other varible in predicting heart diease.









 
