# Visualizations in Statistics

## Advanced Statistics IU
## 2025-04-08 Paul Libbrecht CC-BY

--- 

## The mathematical language

* expresses reasoning with inferences (_this then that_)
* in a way that others recognize a **proof**
	* unambiguous, well-defined, undisputable
* expected to be universal

* but how do you create it?
* how do you trial? how do you explore?
	* meet visualizations!
	* make sure you feed intuition

---

## Visualizations
* Employ the graphical language
* To describe a mathematical story
	* ... with a (mathematical) background
	* employing simple visible coordinates

* Elementary methods:
	* Draw on board
	* Handswaving
	* Sound
* Moments: first shot, visualize in detail, after-thoughts

---

## Data Visualization Ingredients
* A reference system
	* what represent coordinates? planar?
	* how are they marked? (numbers, units, backgrounds)
	* bounds
* Quantity objects
	* dots, curves, surfaces, ...
* Spot objects
	* e.g. a movable cursor
	* extra information
*  often the door to access the detailed data (often tabular)
* often adjustable to change the focus

---

## Visualization Tools Attributes
* Color / Pixelized / Curves
* Static (=> Print), Moving or Dynamically Manipulatable
* Produced by local data?
* Sharable?
* Web-oriented?
* Mobile oriented?

---

## Objects of Visualizations
* Datasets (1 variable, 2 variables, ...)
* Functions  (1 variable, 2 variables, ...)
	* More classical: [Desmos](https://www.desmos.com/calculator), [WolframAlpha](https://www.wolframalpha.com/), [Cabri](https://cabricloud.com/cabriexpress/secondary/), [GeoGebra](https://www.geogebra.org/calculator), [Maple](https://maplesoft.com/), [Matlab](https://www.mathworks.com/)...
	* Necessary to interpret function to decide when to show less or more
* Dependencies between numbers
* Frequency of numbers in places
* Variables may be numeric or categorical, linear order often helps
---

## From Datasets to Plots

* automated tools e.g. 
	* Excel and Spreadsheet, Plotly Dash, Tableau...
* Python libraries: [Bokeh](https://bokeh.org/), [Matplotlib](https://matplotlib.org/), [Shiny](https://shiny.posit.co/)
* Web libraries
	* [Plotly](https://plotly.com/), [Rickshaw](https://tech.shutterstock.com/rickshaw/), [Vega Lite](https://vega.github.io/), [D3](https://d3js.org/), ...
* data exchange oriented: e.g. [CODAP](https://codap.concord.org/), [Datawrapper](https://www.datawrapper.de/), [ObservableHQ](https://observablehq.com/)

---
## Visualizations Risks

* Frustration: A story is a short extract... highlight what you want!
	* Only include data points if useful
		* e.g. remove "outliers"
	* Compensate the fear that reader feels there is not enough
		* allow "exploration"
* Lies: Numbers and scales can go big or small
	* Employing a log-scale can be useful... but... units?
	* Origins of graph at zero? (e.g. [plotly's](https://chart-studio.plotly.com/~demos/1415.embed)) often discouraged
	* psyschology perception for exaggeration and minimization
---

## New Viz

* Steady innovation in order to display various mathematical relations
	* E.g. for 1d-data: Box-and-whiskers, Violin Plot, KDE Curves, see Coursebook
	* e.g. ObservableHQ showcases a lot, a science that keeps innovating
* Dependency between numbers often of interest:
	* Scatter with regression, multiple scatters, 2d-histograms (coursebooks)
	* Confusion matrices, ...
	* Eikosograms (e.g. [NZ census at school](https://new.censusatschool.org.nz/resource/interactive-visualizations-for-conditional-probability/))
* Surprises come in the datasets as well so as to debunk a lot of the false beliefs, e.g. the dino dataset

---

## Histograms
* Remember definition: Only a pile of rectangles with axes
* what do rectangles represent?
	* for a frequency histogram: the amount in the horiz interval
	* for a random variable... the probability of being there
* how broad are rectangles? (the **bins** intervals)
---

## Take away
* Create a visualization to tell a story
* Make sure you have clean data
* Keep scales informative
* Keep iterating between acquisition, cleaning, visualization, story, tell
	* and repeat the loop!
* Favorite counter example PCA (or UMAP):
	* scatter plot or other representation
	* projected on the two __important__ axes... story?

---
