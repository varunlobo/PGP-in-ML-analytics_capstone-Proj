# Post Graduate Program in Machine Learning and Data Analytics offered by IIT-Roorkee 

Final capstone project marking the completion of the Post Graduate Program in ML and Data Analytics

The task at hand was to apply different various algorithms in scikit-learn a build a model to predict the housing price in boston. The data was downloaded from Kaggle. 
The features used were 
Features used for predicting the value of a home in a particular locality are as follows:

ZN           → proportion of residential land (for lots over 25000 sq. ft.) 

INDUS      → proportion of non-retail business acres per town 

NOX         → nitric oxides concentration in the locality(parts per 10 million) 

RM           → average number of rooms per dwelling 

AGE         → proportion of owner-occupied units built prior to 1940 

DIS           → weighted distances to five Boston employment centers 

RAD         → index of accessibility to radial highways 

TAX          → full-value property-tax rate per $10,000 

PTRATIO  → pupil-teacher ratio by town 

Our target variable here is the median price of house i.e. MEDV.

I used the following to build our prediction model
<li> Linear Regression
<li> Support Vector Regression
<li> Random Forest
<li> Decision Tree

For evaluation of 'goodness-of-fit' we used R^2 as the deciding factor. However, we did calculate the Root mean sq error (RMSE) and Mean abs error (MAE) for comparison.

Looks like Random Forest algorithm provided the best R2 value.

![R2 comparison](https://user-images.githubusercontent.com/114509328/199500784-75e215f4-2e23-4d7c-ac1f-5beb1002e580.jpg)


