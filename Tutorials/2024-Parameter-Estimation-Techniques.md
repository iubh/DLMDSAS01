# Parameter Estimation Techniques

## Advanced Statistics Tutorial
## 2024-12-03 Paul Libbrecht [CC-BY](https://creativecommons.org/licenses/by/4.0/)


## We are modelling!
* A common application of mathematics is to MODEL
* Reasoning about the nature of the phenomenon
	* Knowledge from many sources
	* Formulæ and assumptions
* Measure the phenomenon
	* ... adjust the model
	* Using simple or complex recipes

## Let's visualize a parameter estimation

notebook
... start graphically: try multiple parameters around the histogram of a data

TODO: propose a few models and a few estimators

## A parameter estimation recipe
* A process for some distributions
	* Takes the distribution model in account
	* Takes some assumption
	* Takes the data in account; asks you to calculate
	* Proposes a _best value_
* We call an **estimator** such a recipe (or, often, its result)
* For a parameter θ, we call theta-hat its estimated value (sorry, no unicode char); let's use u and û
	* often named **point estimator** 
* Many many conflicting interests

## Basic: Maximum Likelihood Estimator (MLE)
* Have a phenomenon and identified value spaces
* Have a parametrized model:
	* distribution for the values
	* well identified parameters
* Calculate the joint probability of obtaining the given data
	* this becomes a function of the parameters

## MLE Demo
* notebook

## Many other estimators
* Any other _statistics_ can be considered an estimator for a parameter
* Data is not always clean: work on subsamples
	* eg. EM algorithm, sub-sample repeatedly, let converge
* Baeysian approach:
	* Parameters are more or less probable: Prior
	* Data brings the posterior distribution
	* Parameters of the distribution are estimators
* Many more [here](https://en.wikipedia.org/wiki/Estimator#See_also)

## Estimator qualities
- If we know the "true" value u:
	- Bias: E(û) = u
	- Mean-Square-Error, Variance, ...
* Minimum-variance unbiased estimators (MVUE)
	* exist sometimes given a family of distributions
* Baeysian: MAP


