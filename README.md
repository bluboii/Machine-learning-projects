# Machine-learning-projects

This repository contains a compilaiton of fundamental machine learning projects, details of which are as following:

1. Liner Regression project
Problem: look at a demo e-store's data to decide what part of their business shall they focus on more 
Key Steps : 
	
		EDA using seaborn
		Used Scikit learn
		Split train and test data
		Get predictions from the testing data
		Checked predicted values with scatterplot
		Evaluated model performance with:
		Mean Absolute Error, Mean Squared Error 
		Root mean square error and explained variance score
		(high variance is good)
		
		explored residuals to check the distribution
		normal distribution implies good
		
		Created the coefficient table, 
		
		

		
		
2 logistic regression project:
	Problem : Created a prediction model that predicts whether or not a user will click on an ad based off the features of that user
	
		Did some EDA and visualisation
		
		Train test split  
		Used the logistic regression model
		predicted values from test data
		Analysed the model performace with
			confusion matrix
			classification report
			
3. K nearest neighbors project
	performed KNN algorithm on an anonymised classified data"
	
		performed EDA
		standardised the variables
		performed knn to train and test data
		Evaluated the 'k' value performaces with elbow method
		optimised k value for the lowest Error Rate
		analysed confusion matrix and classification report
		
4. decision trees and Random forest project

	 explored data from LandingClub.com (2007 to 2010)
	 We tried to predict weather the loan was fully paid back or not
	 
	 EDA, visualisations with pandas and seaborn
	 made dummy variables for catagorical columns
	 train test split
	 
	 trained a decision tree model
	 predicted values for the test data
	 checked confusion matrix and classification report
	 
	 
	 trained Random Forest model with 300 estimators
	 predicted the values on the test data
	 checked the confusion matrix and classification report 
	 
	 
5. Support vector machines project
	worked on the iris flower dataset (imported from seaborn collection)
	tried to predict the species of flower with given features
	
	did some EDA to understand the data
	train test split
	
	train the SVC model from sklearn
	evaluated the model predictions from confusion matrix and classification report
	
	optimised C and Gamma values using Gridsearch
	predicted values using grid matrix
	evaluated using confusion matric and classification report
	
6. K means clustering project
	Used dummy data to cluster private and public univerities
	EDA- seaborn, matplotlib
	Trained a Kmeans model and predicted 2 clusters
	Evaluated the model using confusion matrix and classification report 
