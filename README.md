# Model Building Life Cycle
## Model Building Stages
* Problem definition
* Hypothesis Generation
* Data Extraction/Collection
* Data Exploration and transformation
* Predictive modeling
	- Algorithmic Selection
	- Training Model

## Model Building Steps

* Univariate Analysis : Classify the data as continuous or categorical
	- Continuous Variable : In case of continuous variables, we generally focus on measure of central tendency and spread of data such as Mean, Median, Range, IQR and Standard Deviation. Lets implement them using Pandas in python.
	- Categorical : In case of categorical variables, we generally use frequency table to understand distribution of each category. 
* Multivariate Analysis : Multivariate Analysis finds out the relationship between two or more variables. Here, we look for association and disassociation between variables at a pre-defined significance level.The type of visualization technique to use depends on the type of each variable. Thus there can be 3 combinations of the type of the 2 variables:
	- categorical - categorical : We can do cross tabulation or use confusion matrix
	- continuous - continuous : We can use scatter plot to see if there is some significant relation
	- categorical - continuous : we can use box plot
* Missing Value Treatment - replacing the missing values with mean ro mode
* Outlier Treatment - like trimming the top and bottom 10% of data
* Predictive Modeling
	-Date PreProcessing -like labelencoder
	-Fit Model
	-Make Predictions
	-Analyze Results
