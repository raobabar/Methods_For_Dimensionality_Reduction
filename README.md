# Methods_For_Dimensionality_Reduction

Dimensionality reduction:
It means reduce the number of columns/ number of features.

There are 12 common methods for feature engineering or dimensionality reduction:


1. Percent missing value:

Drop that variables that have high %age of missing values.
Steps:
Create binary indicators to denote missing and non-missing values, and then visualize this to eliminate those columns.

2. Amount of variation:

Drop or review the variables that have a very low variation.
Steps:
Either standardize all the variables, or use standard deviation to see the variations, and then drop the variables with zero variation.

3. Pairwise correlation:

Many variables are often correlated with each other, and hence are redundant. If two variables are highly correlated with each other, keeping only one will help reduce dimensionality without much loss of information.
Steps:
The one that has a lower correlation coefficient with the target should be eliminated.

4. Multicolinearity

5. PCA

6. Cluster analysis

7. Correlation with the target:

If the variable has a very low correlation with the target, it's not gonna useful for the model to predict.

8. Forward selection:

Steps:
a) Identify the best variable based on model accuracy. 
b) Add the next best variable into the model. 
c) And so on until you meet some predefined criteria, whether that criteria is based on some threshold value or some number of features.

9. Backward elimination: 

Steps:
a) Start putting all variables into the model. 
b) Drop at least useful variable based on smallest drop in model accuracy. 
c) And so on until some predefined criteria is satisfied.

10. Stepwise selection:

It's kind of a combination of Forward and Backward selection.

11. LASSO:

"Least Absolute Shrinkage and Selection Operator". It is a model for creating a regularized linear model. You may have heard of LASSO regression or rich regression. There are two types of regularization.

12. Tree-based selection:

With ensembles of trees, of decision trees, such as random forest. Forests of trees to evaluate the importance of features and fit a number of randomized decision trees on various sub-samples of the dataset and ue averaging to rank order features.
