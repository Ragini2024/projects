# predict profit using post method
# projects
Profit prediction :
Following are the steps involve in profit prediction project using machine learning, python, flask.
•	Data problem
•	Data collection
•	Exploratory Data Analysis
•	Sampling
•	Model creating
•	Tuning with hyper-parameter
•	Deployment using flask
Data collection: collecting data from various sources. In this project I have used dataset given by my training institute.
EDA: 
•	EDA stands for exploratory data analysis.
•	Data pre-processing: here in data pre-processing we have various technique such as treatment of missing data, outlier detection, encoding. 
•	With the help of isnull().sum(), i have checked whether the missing value is there in data set or not. The dataset which i have used in profit prediction has no missing values present in it.
•	For converting categorical features into continues feature we have two techniques. First is label encoding and the other one is one hot encoding. Here i have used one hot encoding.
•	Uni-variate analysis: analysis of a single column is known as univariate analysis.
•	Bi-variate analysis:  analysis of two columns is called bivariate analysis. Here i have done this bivariate analysis to check relation between features, i.e linear or non-linear.
•	Correlation : here for finding correlation a i have used corr()function, and heatmap.
Sampling: selecting a chunk of dataset instead of selecting whole dataset is known as sampling.
Model: here in this project i have used Random Forest Classifier Algorithm. It is a multiple tree algorithm.
Reason behind selecting this particular algorithm:
•	Skew of data does not matter
•	Feature importance 
•	Multiple trees are created parallel, hence it is faster than other ensemble methods. 
In model creation i have done is splitting the dataset into training and testing set. Then evaluated the model accuracy.
Tuning: for hyper-parameter tuning i have used Grid Search CV to find out the best parameter and to improve the accuracy of the model. 
Deployment: for the deployment of model i have used flask and flasgger api. First i have created the pickle file of the model which is used for serialization and then i made a flask application and finally done the deployment process using flask. 



