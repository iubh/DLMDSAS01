# Bayesian Approach and Errors

## Advanced Statistics Tutorial
## 2025-07-31 Paul Libbrecht CC-BY
--- 

## Modelling
* We know of a phenomenon
* ... knowledge gives us its principles
* ... but variables remain
* Classic task: Let experiment clear variables
	* find variables that are probable considering experiments
	* often called parameter estimations
	* find the "the best" parameters
* But how to evaluate best?
--- 
## Simple Example: Throw a Dice
* Many expect a dice to be yield a uniform distribution, but some dice are biassed
	* How much biassed?
	* Assume one face preferred
		* so P(X=k) = α, P(X≠k) = (1-α) uniform among the 5 (each (1-α)/5)
	* Experiment, obtain likelihood, get α and k so likelihood is maximum
* But can this be really any k or α?
	* What if an insider tells us: The dice is made to favour small value?
	* What if the constructing company tells us that the surface differences are mostly low?
	* then we could measure a different probability for each possible k or α...
* Bayesian statistics pulls more knowledge in!
---

## Schematic of a Bayesian Approach

* (as before): Select a model and its parameters
* (as before): Run "enough" experiments
* Extract knowledge to calculate a prior of the parameters: 
	* similar studies, nose estimates, simulations, ...
* Devise likelihood and posterior
* Display and use posterior
	* find "best" (posterior's max, expectation...)
	* but also envision how probable are similar answers
* Repeat!
	* use other priors
	* take less or more samples
	* obtain more convincing evidence
---
## Example resolution: Seller's Interview

...

---
## Common Errors
* Calculations are more complex: Tame the beast! Use conjugates... Use numerical tools...
* Priors are uncertain: Make sure you know of other studies; try alternative priors; investigate the broad possibilities: do they make sense?
* Use a single method: the Baysian Approach is a conceptual approach. Only apply when you understand!
