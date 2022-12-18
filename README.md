# Boston Housing Dataset Prediction

Boston Housing Dataset Predicting Median value of owner-occupied homes The aim of this assignment is to learn the application of machine learning algorithms to data sets. This involves learning what data means, how to handle data, training, cross validation, prediction, testing your model, etc. This dataset contains information collected by the U.S Census Service concerning housing in the area of Boston Mass. It was obtained from the StatLib archive, and has been used extensively throughout the literature to benchmark algorithms. The data was originally published by Harrison, D. and Rubinfeld, D.L. Hedonic prices and the demand for clean air', J. Environ. Economics & Management, vol.5, 81-102, 1978. The dataset is small in size with only 506 cases. It can be used to predict the median value of a home, which is done here. There are 14 attributes in each case of the dataset.

They are:

1.CRIM - per capita crime rate by town
2.ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
3.INDUS - proportion of non-retail business acres per town.
4.CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
5.NOX - nitric oxides concentration (parts per 10 million)
6.RM - average number of rooms per dwelling
7.AGE - proportion of owner-occupied units built prior to 1940
8.DIS - weighted distances to five Boston employment centres
9.RAD - index of accessibility to radial highways
10.TAX - full-value property-tax rate per  10,00011.PTRATIO−pupil−teacherratiobytown12.B−1000(Bk−0.63)2whereBkistheproportionofblacksbytown13.LSTAT−14.MEDV−Medianvalueofowner−occupiedhomesin 1000's

Aim

● To implement a linear regression with regularization via gradient descent.

● to implement gradient descent with Lp norm, for 3 different values of p in (1,2]

● To contrast the difference between performance of linear regression Lp norm and L2 norm for these 3 different values.

● Tally that the gradient descent for L2 gives same result as matrix inversion based solution. All the code is written in a single python file. The python program accepts the data directory path as input where the train and test csv files reside. Note that the data directory will contain two files train.csv used to train your model and test.csv for which the output predictions are to be made. The output predictions get written to a file named output.csv. The output.csv file should have two comma separated columns [ID,Output].
