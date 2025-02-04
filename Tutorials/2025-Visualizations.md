# Visualizations in Statistics

## Advanced Statistics IU
## 2025-02-04 Paul Libbrecht CC-BY

--- 

## The mathematical language

* expresses reasoning with inferences (_this then that_)
* in a way that others recognize a **proof**
	* unambiguous, well-defined, undisputable
* expected to be universal

* but how do you create it?
* how do you trial?
* how do you explore?
	* meet visualizations!

---

## Visualizations
* Employ the graphical language
* To describe a mathematical story
	* ... with a (mathematical) background
* Solution 1: Waving hands
	* manipulations of formulæ
	* observing geometric configurations
	* good for discourse, good for sharing stories' high points
	* ... but volatile, difficult for reflection

---

## Visualizing Real Functions
* Given f : ℝ → ℝ, associating to each x ∈ ℝ an y ∈ ℝ
* Makes a _graph_: 
	* a set of points for each point of the definition domain
	* even if the function is not continuous!

* Can see approximately:
	* when it is high or low
	* when it is at maximum or minimum
	* when it goes to asymptotes

---

## Tools to Visualize Real Functions
* Many many tools. Let's try with sin(1/x²)
* Can simply start with the basics: 
	* whatever crafted (e.g. with matplotlib's lines as in [tutorial](https://matplotlib.org/stable/tutorials/pyplot.html) or vega-lite or plotly
	* gnuplot
* Fundamental: axes to show the scales
* Makes surprises already
* More classical: [Desmos](https://www.desmos.com/calculator), [WolframAlpha](https://www.wolframalpha.com/), [Cabri](https://cabricloud.com/cabriexpress/secondary/), [GeoGebra](https://www.geogebra.org/calculator), [Maple](https://maplesoft.com/), [Matlab](https://www.mathworks.com/)...
* Necessary to interpret function to decide when to show less or more
---

## Visualizing Multi-dimensional Functions

* From ℝ² to  ℝ
	* surfaces in space
	* not all visible
	* doable in some cases with some tools (e.g. Maple or WolframAlpha, e.g. [here](https://www.wolframalpha.com/input?i=plot+sin%281%2Fx%C2%B2%2B1%2Fy%C2%B2%29))
	* partial derivatives become quickly difficult!
* ... but for ℝ³ ? to ℝ² ? higher?
	* barely known how to represent
	* derivative: linear mappings that approximate

---

## Visualizing 1D-Data Sets

- data-set by balls:
	- works well if very few
	- e.g. pyplot.scatter with constant y
- idea: add some jitter:
	- vertical random, to see where there's more

---
## Variates

* Given a random-variable distribution
	* as a density, CDF or PMF
	* ... obtain a method to generate a set of points
* e.g. random's functions ([here](https://docs.python.org/3/library/random.html#discrete-distributions))

---

## Calculating Variates

* Question: given a PDF f
* how can I generate a sample measurable as f?
	* ... i.e. create a _variate_
* Use transformation theorem: _Inverse transform sampling_ (Smirnov transformation)
	* given a random variable X with CDF Fₓ  the random variable  Fₓ⁻¹∘U has the same distribution as X
	* see https://en.wikipedia.org/wiki/Inverse_transform_sampling