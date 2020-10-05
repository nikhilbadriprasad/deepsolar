# deepsolar-analysis

The main task of the project is to predict the target variable in the given data set using supervised classification methods given the set of predictive variables. The complete data analysis is carried out with those supervised methods explained in the course, finally, the best model is chosen with the highest accuracy.

The dataset used here is a subset of the DeepSolar database, a solar installation database for the US, built by extracting information from satellite images, consisting of 20736 obs and 81 variables out of which 18 are non-numeric variables and 62 are numeric.The main aim is to predict the solar power system coverage using solar_system_count(binary variable) as the target variable.

Supervised classification method is used because it is the process of predicting the target variables using a function of input variables.The six methods used here are svm, logistic regression, boosting, bagging, random forest and classification tree.The complete analysis is performed on the dataset.Finally,Hold out sample method of cross-validation is used to evaluate the relative merits of range of classification methods used.


