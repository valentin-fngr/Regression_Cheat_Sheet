
# Regression_Cheat_Sheet

 1. Distribution Transformation
 2. Feature Engineering :


## 1 ) **Distribution Transformation** :
	

 - **Log Transformation** : 
	 - **definition** : Using the logarithm of one or more variables instead of the un-logged form makes the effective ***relationship non-linear***, while ***still preserving the linear model***.
	 - **Shape** :  ***Convert*** the ***distribution*** into a shape that looks like a ***normal distribution***. Log transform can make highly skewed distributions ***less skewed***
	 - **why ?** : Algorithms can be sensitive to such distribution of values and can under perform if the range is not properly normalized.
	 - **conditions** : Positively distributed Variable

## 2 ) **Feature Engineering** :

 - **Simplifications** : 
	- **Encoding** : is a ***required*** ***pre-processing*** step when working with categorical data for machine learning algorithms
	- **Ordinal** : Feature is ***ordinal***  + ***too much categorical*** feature
	- **One Hot Encoding** : feature is ***not ordinal*** + ***cannot*** be ***measured***
 - ***Combinations*** : 
