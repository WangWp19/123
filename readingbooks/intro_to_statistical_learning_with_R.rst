*************************************************************
An introduction to statistical Learning with Application in R
*************************************************************

.. sidebar:: Contents

    .. contents::      		    	

        

1. Introduction
---------------  

::

    statistical tools can be classified as "supervised" or "unsupervised".
    supervised statistical learning involves building a statistical model for pr
    edicting,
    or extimating. 


1.1. an overview of statistical learning
****************************************



2. Statistical learning
-----------------------
 		   		
2.1. What is statistical learning?
**********************************

2.1.1. why estimate f?
^^^^^^^^^^^^^^^^^^^^^^
 
2.1.2. how do we estimate f?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.1.3. The trading-off between prediction accuracy and model interpretability
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.1.4. supervised versus unsupurvised learning
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.1.5. regression versus classification problems
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
 
2.2. Assessing model accuracy
*****************************

2.2.1. Measuring the quality of fit
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.2.2. the bias- variance trade-off
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.2.3. the classification setting
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
                   
2.3. Lab:Introduction to R
**************************

2.3.1. Basic commands
^^^^^^^^^^^^^^^^^^^^^

2.3.2. Graphics
^^^^^^^^^^^^^^^

2.3.3. Indexing Data
^^^^^^^^^^^^^^^^^^^^
 
2.3.4. Loading data
^^^^^^^^^^^^^^^^^^^

2.3.5. Additional graphical and numerical Summaries
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.4. Exercises
**************

3. linear regression
--------------------

3.1. simple linear regression
*****************************

3.1.1. estimating the coefficients
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.1.2. assessing the accuracy of the coefficient estimates
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.1.3. assessing the accuracy of the model
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.2. Multiple Linear Regresion
******************************

3.2.1. Estimating the regression coefficients
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.2.2. some important questions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.3. other considerations in the regression model
*************************************************

3.3.1. quality predictiors
^^^^^^^^^^^^^^^^^^^^^^^^^^

3.3.2. extensions of the linear model
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.3.3. potential problems
^^^^^^^^^^^^^^^^^^^^^^^^^

3.4. the marketing plan
***********************

3.5. comparison of linear regression with K-nearest neighbors
*************************************************************

3.6. Lab: Linear regresion
**************************

3.6.1. libraries
^^^^^^^^^^^^^^^^

3.6.2. simple linear regression
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.6.3. multiple linear regression
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.6.4. interaction terms
^^^^^^^^^^^^^^^^^^^^^^^^

3.6.5. non-linear transformations of the predictiors
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.6.6. qualitative predictors
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.6.7. writing functions
^^^^^^^^^^^^^^^^^^^^^^^^

3.7. exercises
**************

4. classification
-----------------
 
4.1. an overview of classification
**********************************

4.2. why not linear regression
******************************

4.3. logistic regression
************************

4.3.1. the logistic model
^^^^^
4.3.2. estimating the regression coefficients
^^^^^

4.3.3. making predictions
^^^^^^^^^^^^^^^^^^^^^^^^^

4.3.4. multiple logistic regression
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.3.5. logistic regression for > 2 response classes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.4. linear discriminant analysis
*********************************

4.4.1. using bayes' theorem for classification
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.4.2. linear discriminant analysis for p =1
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.4.3. linear discriminant analysis for p >1
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.4.4. quadratic discriminant analysis
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.5. a comparison of classification methods
*******************************************

4.6. Lab: Logistic regression, LDA, QDA, and KNN
************************************************

4.6.1. The stock market data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.6.2. logistcal regression
^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.6.3. linear discriminant analysis
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.6.4. quadratic discriminant analysis
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.6.5. K- nearest neighbors
^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.6.6. an application to caravan Insurance Data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.7. exercise
*************

5. Resampling methods
---------------------

5.1. cross-validation
*********************

5.1.1. the validation set approach
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

5.1.2. Leave-one-out cross-validation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

5.1.3. k-fold cross-validation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

5.1.4. Bias-variance trade-off for k-fold cross-validation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

5.1.5. cross-validation on classification problems
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

5.2. the Bootstrap
******************

5.3. Lab: cross-validation and the bootstrap
********************************************

5.3.1. the validation set approach
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

5.3.2. leave-one-out cross-validation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

5.3.3. k-fold cross-validation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

5.3.4. the bootstrap
^^^^^^^^^^^^^^^^^^^^

5.4. the exercise
*****************

6. linear model selection and regularization
--------------------------------------------

6.1. subset selection
*********************

6.1.1. best subset selection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.1.2. stepwise selection
^^^^^^^^^^^^^^^^^^^^^^^^^

6.1.3. choosing the optimal model
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.2. shrinkage methods
**********************

6.2.1. ridge regression
^^^^^^^^^^^^^^^^^^^^^^^

6.2.2. the lasso
^^^^^^^^^^^^^^^^

6.2.3. selecting the tuning parameter
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.3. dimension reduction methods
********************************

6.3.1. principal components regression
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.3.2. partial least squares
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.4. considerations in high dimensions
**************************************

6.4.1. high-dimensional data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.4.2. what goes wrong in high dimensions?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.4.3. regression in high dimensions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.4.4. interpreting results in high dimensions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.5. Lab 1: Subset selection methods
************************************

6.5.1. Best subset selection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.5.2. forward and backward stepwise selection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.5.3. choosing among models using the validation set approach and cross-validation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.6. lab2: ridge regression and the lasso
*****************************************

6.6.1. ridge regression
^^^^^^^^^^^^^^^^^^^^^^^

6.6.2. the lasso
^^^^^^^^^^^^^^^^

6.7. lab3 : PCR and PLS Regression
**********************************

6.7.1. principal components regression
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.7.2. partial least squares
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.8. exercises
**************

7. moving beyond linearity
--------------------------

7.1. polynominal regression
***************************

7.2. step functions
*******************

7.3. basis functions
********************

7.4. regression splines
***********************

7.4.1. piecewise polynomials
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

7.4.2. constraints and splines
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

7.4.3. the splines basis representation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

7.4.4. choosing the number and locations of the knots
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
 
7.4.5. comparison to polynomial regression
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

7.5. smoothing splines
**********************

7.5.1. an overview of smoothing splines
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

7.5.2. chossing the smoothing parameter lamda
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

7.6. local regression
*********************

7.7. generalized additive models
********************************

7.7.1. GAMS for regression problems
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

7.7.2. GAMS for classification problems
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

7.8. Lab: Non-linear modeling
*****************************

7.8.1. polynomial regression and step functions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

7.8.2. splines
^^^^^^^^^^^^^^

7.8.3. GAMS
^^^^^^^^^^^

7.9. Exercises
**************

8. Tree-Based methods
---------------------

8.1. the basics of decision trees
*********************************

8.1.1 regression trees
^^^^^^^^^^^^^^^^^^^^^^

8.1.2. classification trees
^^^^^^^^^^^^^^^^^^^^^^^^^^^

8.1.3. trees versus linear models
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

8.1.4. advantage and disadvantage of trees
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

8.2. bagging, random forests, boosting
**************************************

8.2.1. bagging
^^^^^^^^^^^^^^

8.2.2. random forests
^^^^^^^^^^^^^^^^^^^^^

8.2.3. boosting
^^^^^^^^^^^^^^^

8.3. lab:decision trees
***********************

8.3.1. fitting classification trees
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

8.3.2. fitting regression trees
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

8.3.3. bagging and random forests
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

8.3.4. boostingg
^^^^^^^^^^^^^^^^

8.4. Exercises
**************

9. support vector machines
--------------------------

9.1. maximal margin classifier
******************************

9.1.1. what is a hyperplane?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.1.2. classification using a seperating hyperplane
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.1.3. the maximal margin classifier
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.1.4. construction of the maximal margin classifier
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.1.5. the non-seperable case
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.2. support vector classifiers
*******************************

9.2.1. overview of the support vector classifier
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.2.2. details of the support vector classifier
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.3. support vector machines
****************************

9.3.1. classification with non-linear decision boundaries
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.3.2. the support vectoe machine
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.3.3. an application to the eart disease data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.4. SVMs with more than two classes
************************************

9.4.1. one-versus-one classification
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.4.2. one-versus-all classification
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.5. relationship to logistic regression
****************************************

9.6. lab:support vector machines
********************************

9.6.1. support vector classfier
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.6.2. support vector machine
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.6.3. ROC curves
^^^^^^^^^^^^^^^^^

9.6.4. SVM with multiple classes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.6.5. application to the gene expression data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

9.7. exercises
**************

10. Unsupervised learning
-------------------------

10.1. the challenge of unsupervised learning
********************************************

10.2. principal components analysis
***********************************

10.2.1. what are principal components?-
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

10.2.2. another interpretation of principal components
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

10.2.3. More on PCA
^^^^^^^^^^^^^^^^^^^

10.2.4. Other uses for principal components
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

10.3. clustering methods
************************

10.3.1. K-means clustering
^^^^^^^^^^^^^^^^^^^^^^^^^^

10.3.2. Hierarchical clustering
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

10.3.3. practical Issues in clustering
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

10.4. Lab1: principal components analysis
*****************************************

10.5. lab2: clustering
**********************

10.5.1. K-means clustering
^^^^^^^^^^^^^^^^^^^^^^^^^^

10.5.2. Hierarchical clustering
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

10.6. Lab3: NCI60 Data example
******************************

10.6.1. PCA on the NCI60 data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

10.6.2. clustering the observations of the NCI60 data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

10.7. exercises
***************
   		 

