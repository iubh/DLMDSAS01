# Regressions

## Advanced Statistics Tutorial
## 2024-07-11 Paul Libbrecht CC-BY
--- 
## Typical Statistical Process
* Most statistical processes go about so:
	* Have theoretical knowledge about experiment
	* Some parameters remain (hypotheses, theta, ...)
	* Experiment gives you food
	* Exp-Data digested by a method
		* => _Most_ probable parameters
* E.g. Maximum Likelihood
* Quite often so: A parametrized function
	* ==data==method==> Decided parameters
	* regression is exactly doing this: parametrized function, sample values, _best_ parameters
--- 
## Linear Regression
* Parametrized linear function
	* e.g. a linear form φ:|Rⁿ → |R
	* (expressed as a vector of n reals a₁, ..., aₙ)
* Some points of the graph (x₁, y₁= φ(x₁)), ...
* What is the _best_ value for a₁, ..., aₙ
	* e.g. so that the sum of distance y₁ to φ(x₁) is minimized?
		* same as sum of square
	* e..g. ...
* https://cabricloud.com/cabriexpress/
* blackboard, computer, visualize!
* meet outlier, ...
--- 
## Polynomial Regression
* Easy: instead of a vector, a polynomial function of one variable
* Same problem, same solution
* ... think: of multiple variables?
* concrete example: polynomial regression
* See [Regressions.ipynb](Regressions.ipynb)
* meet overfitting, perspective loss, ...

--- 
## Other Costs Functions
* Practically: it's all about finding a minimum
	* of the sum of squares
* or of another function: regularization
	* idea: take in account the size of the parameters
* as in coursebook sec 6.4
* and any other function works too!
--- 
## Regularization Options
* ridge: sum of squares of parameters
* lasso: sum of abs-values of parameters
* more complex 
	* ... same computer programme
* which penalty coefficient? (λ): it depends on practice
	* best is to try and visualize
	* too strong λ => everything flat
--- 
## Take Away
* Regression as a simple function approximation method
* Always based on a penalty function
* Penalty can be the distance to the points
	* ... with amplitude of the parameters
	* ... with what more you think??
	* space for imagination!

---