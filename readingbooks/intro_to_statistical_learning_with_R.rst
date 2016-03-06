*************************************************************
An introduction to statistical Learning with Application in R
*************************************************************

Contents
========

1. Introduction
2. Statistical learning
   		1. What is statistical learning?
   		   
   		    	1. why estimate f?
   		    	2. how do we estimate f?
   		    	3. The trading-off between prediction accuracy and model interpretability
   		    	4. supervised versus unsupurvised learning
   		    	5. regression versus classification problems
   		    	   
   		2. Assessing model accuracy

   				1. Measuring the quality of fit
   				2. the bias- variance trade-off
   				3. the classification setting
   		   				   
   		3. Lab:Introduction to R
   		   
   		   		1. Basic commands 
   		   		2. Graphics
   		   		3. Indexing Data
   		   		4. Loading data
   		   		5. Additional graphical and numerical Summaries
   		   		   
   		4. Exercises
   		   
3. linear regression
   
   	    1. simple linear regression
   	       
   	       		1. estimating the coefficients
   	       		2. assessing the accuracy of the coefficient estimates
   	       		3. assessing the accuracy of the model
   	       		   
   	    2. Multiple Linear Regresion
   	       
   	    		1. Estimating the regression coefficients
   	    		2. some important questions
   	    		   
   	    3. other considerations in the regression model
   	       	
   	       		1. quality predictiors
   	       		2. extensions of the linear model
   	       		3. potential problems
   	       		   
   	    4. the marketing plan
   	    5. comparison of linear regression with K-nearest neighbors
   	    6. Lab: Linear regresion
   	       
   	       		1. libraries
   	       		2. simple linear regression
   	       		3. multiple linear regression
   	       		4. interaction terms
   	       		5. non-linear transformations of the predictiors
   	       		6. qualitative predictors
   	       		7. writing functions
   	       		   
   	    7. exercises
   	       
4. classification
   
   		1. an overview of classification
   		2. why not linear regression
   		3. logistic regression
   		   
   		   		1. the logistic model
   		   		2. estimating the regression coefficients
   		   		3. making predictions
   		   		4. multiple logistic regression
   		   		5. logistic regression for > 2 response classes
   		   		   
   		4. linear discriminant analysis
   		   
   		   		1. using bayes' theorem for classification
   		   		2. linear discriminant analysis for p =1 
   		   		3. linear discriminant analysis for p >1
   		   		4. quadratic discriminant analysis 
   		   		   

   		5. a comparison of classification methods 
   		6. Lab: Logistic regression, LDA, QDA, and KNN
   		   
   		   		1. The stock market data
   		   		2. logistcal regression
   		   		3. linear discriminant analysis
   		   		4. quadratic discriminant analysis 
   		   		5. K- nearest neighbors
   		   		6. an application to caravan Insurance Data
   		   		   
   		7. exercise
   		   
 5. Resampling methods
    
    	1. cross-validation
    	   
    	        1. the validation set approach
    	   		2. Leave-one-out cross-validation
    	   		3. k-fold cross-validation
    	   		4. Bias-variance trade-off for k-fold cross-validation
    	   		5. cross-validation on classification problems
    	   
    	2. the Bootstrap
    	3. Lab: cross-validation and the bootstrap
    	   
    	   		1. the validation set approach
    	   		2. leave-one-out cross-validation
    	   		3. k-fold cross-validation
    	   		4. the bootstrap
    	   		   
    	4. the exercise
    	   
6. linear model selection and regularization
   
   		1. subset selection
   		   
   		   		1. best subset selection
   		   		2. stepwise selection
   		   		3. choosing the optimal model
   		 
   		2. shrinkage methods
   		    	
   		    	1. ridge regression
   		    	2. the lasso
   		    	3. selecting the tuning parameter
   		    	   
   		3. dimension reduction methods
   		    	
   		    	1. principal components regression
   		    	2. partial least squares
   		    	
		4. considerations in high dimensions
		   
		   		1. high-dimensional data
		   		2. what goes wrong in high dimensions?	
		   		3. regression in high dimensions
		   		4. interpreting results in high dimensions
		   		  
		5. Lab 1: Subset selection methods
		   
		   		1. Best subset selection
		   		2. forward and backward stepwise selection
		   		3. choosing among models using the validation set approach and cross-validation
		   		   
		6. lab2: ridge regression and the lasso
		
				1. ridge regression
				2. the lasso
				   
	    7. lab3 : PCR and PLS Regression
	       
	       		1. principal components regression
	       		2. partial least squares
	       		   
	    8. exercises
	       
7. moving beyond linearity
   
   		1. polynominal regression
   		2. step functions
   		3. basis functions
   		4. regression splines
   		   	
   		   		1. piecewise polynomials
   		   		2. constraints and splines
   		   		3. the splines basis representation
   		   		4. choosing the number and locations of the knots
   		   		5. comparison to polynomial regression
   		   		   
   		5. smoothing splines
   		   
   		   		1. an overview of smoothing splines
   		   		2. chossing the smoothing parameter lamda
   		 
   		6. local regression
   		7. generalized additive models
   		   
   		   		1. GAMS for regression problems
   		   		2. GAMS for classification problems
   		   		
   		8. Lab: Non-linear modeling
   		    
   		    	1. polynomial regression and step functions
   		    	2. splines
   		    	3. GAMS
   		    	   
   		9. Exercises
   		    
8. Tree-Based methods
   		
   		1. the basics of decision trees
   		   
   		   		1. regression trees 
   		   		2. classification trees
   		   		3. trees versus linear models
   		   		4. advantage and disadvantage of trees
   		   		   
   		2. bagging, random forests, boosting
   		   
   		   		1. bagging
   		   		2. random forests
   		   		3. boosting
   		   		   
   		3. lab:decision trees
   		   
   		   		1. fitting classification trees
   		   		2. fitting regression trees
   		   		3. bagging and random forests
   		   		4. boostingg
   		   		   
   		4. Exercises
   		   
9. support vector machines
    
    	1. maximal margin classifier
    	   
    	   		1. what is a hyperplane?
    	   		2. classification using a seperating hyperplane
    	   		3. the maximal margin classifier
    	   		4. construction of the maximal margin classifier
    	   		5. the non-seperable case
    	   		   
    	2. support vector classifiers
    	   
    	   		1. overview of the support vector classifier
    	   		2. details of the support vector classifier
    	   		   
    	3. support vector machines
    	   
    	   		1. classification with non-linear decision boundaries
    	   		2. the support vectoe machine
    	   		3. an application to the eart disease data
    	   		   
    	4. SVMs with more than two classes 
    	   	
    	   		1. one-versus-one classification
    	   		2. one-versus-all classification
    	  
    	5. relationship to logistic regression
    	6. lab:support vector machines
    	   
    	   		1. support vector classfier
    	   		2. support vector machine
    	   		3. ROC curves 
    	   		4. SVM with multiple classes
    	   		5. application to the gene expression data
    	   		   
    	7. exercises
    	
10. Unsupervised learning
    
    	1. the challenge of unsupervised learning
    	2. principal components analysis
     			
     			1. what are principal components?-
     			2. another interpretation of principal components
     			3. More on PCA
     			4. Other uses for principal components
     			   
        3. clustering methods

             	1. K-means clustering
             	2. Hierarchical clustering
             	3. practical Issues in clustering
             	   
        4. Lab1: principal components analysis
        5. lab2: clustering

                1. K-means clustering
             	2. Hierarchical clustering
        
        6. Lab3: NCI60 Data example
          
          		1. PCA on the NCI60 data
          		2. clustering the observations of the NCI60 data
          		   
        7. exercises

             	    
     			   
    	   		
   		   		   


   		   		 


   		   		   



   		 

