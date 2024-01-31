# Curse of Dimensions

## Advanced Statistics Tutorial
## 2024-01-31 Paul Libbrecht CC-BY
--- 

## Trade-off

* Accept current state of data?
* Ask for more data?
	* ... more samples?
	* ... more "questions"?
		* that makes more dimensions!
		* warning


--- 
## Simple dimension evolution

* slides
* coursebook sec 1.5

---
## How to "avoid the curse of dimension"
* have lots of sample
* avoid more dimensions
	* but beware: Simpson's paradox (see [Arte's presentation](https://www.arte.tv/fr/videos/107398-002-A/voyages-au-pays-des-maths/) in French)
* avoid more questions

---
## Ways out of the dimensions 
* PCA / LDA (see coursebook)
	* Extracts most discriminating directions 
	* Beware dimensions that are composite
* Feature reductions (machine learning's)

---
## Examples with the Iris Dataset

* Historical background (~1930)
	* [RA Fischer](https://en.wikipedia.org/wiki/Ronald_Fisher)
	* Journal of Eugenics
* The [Iris dataset's publication](https://en.wikipedia.org/wiki/Iris_flower_data_set)
* See coursebook

* Troubles with this
* Alternative datasets: [Palmer's Penguins](https://allisonhorst.github.io/palmerpenguins/articles/intro.html)

---
## Wrap-up

* Dimensions explose easily
* ... and explosion is exponential
* Reducing dimensions has strategies
	* ... but may disorient
* Going up and down will be classic in your work