# Terrorist_Group_Prediction  WIP
Predicting Terrorist group using global terrorism dataset by simple machine learning models.

The model uses tokenize summary and details about weapon used, country, vincity, attack type, summary etc.
Summary was tokenized and used as a feature
target values were label encoded for classification.

Some simple Machine Learning models were utilized like Decision Trees, SGD Classifier and KNN ==>
Accuracy 76% (MAX)

#New Update..
In the notebook GTD_Prediciton, Keras Functional API was used to create a model that concantates two separate dense layers.
The catagorical data and summary tokens are now seaparately processed and then combined into a several dense layers. ==>
Accuracy 85%
