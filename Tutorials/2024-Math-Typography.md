# Mathematical Typography

## Advanced Statistics IU
## 2024-12-20 Paul Libbrecht CC-BY

--- 

## The mathematical language

* expresses reasoning
* with inferences (_this then that_)
* in a way that others recognize a **proof**
	* unambiguous
	* well-defined
	* undisputable
* expected to be universal
	* but the language and the known definitions are culture specific
	* e.g. Thales Theorem
---
## Formulæ

* Mathematics often uses formulæ instead of words
	* Useful to manipulate elementary operations
	* Useful to express functions, equations, models, ...
* Archimedes principle: words vs graphics vs formulæ e.g. on the wikipedia page https://en.wikipedia.org/wiki/Archimedes%27_principle
* Chalkboard still the norm for a mathematicain
* Formulæ have a "haptic": you can move them
* ... slides
* invent new notations is allowed
---
## Formulæ Typography

See workbook extra info.
Represented by TeX or by MathML
Remember: displaystyle, textstyle, scriptstyle, scriptscriptstyle

--- 

## What is LaTeX?

* TeX: written by Donald Knuth in the 70s
* Compile plain-text source to something printable
* Strong typography talent, esp for mathematical formulæ
* Expandability through macros
* LaTeX: an abstraction of TeX for flexible layout
	* table of contents, sections, uniform styles, different macros
	* Founded by Leslie Lamport
	* Now accepted as standard
* LaTeX and TeX: a project of the [TUG](https://tug.org)
	* with a huge set of extensions: [CTAN](https://www.ctan.org/)


- - -
## Getting LaTeX: macOS and Unixes

* Warning: large eco-system... does take a lot of had-disk
* [TeXlive](https://en.wikipedia.org/wiki/TeX_Live) is the distribution!
	* available for macPorts, homebrew, debian, ubuntu, ...
* Typical commands that come with
	* latex (produces DVI)
	* pdflatex (most spread)
* Includes fonts, styles, standard packages, ...
* Complement it with a desktop app: TeXShop


- - -
## Getting LaTeX: Windows

* Either use the Linux subsystem
	* all Linux commands apply
	* careful: it is a container within Windows
	* ... 
* Or use [MikTeX](https://miktex.org/)
* Includes a desktop programme


- - -

## Starting with LaTeX

* Choose a very simple project first
	* e.g. four lines
			\documentclass{article}
			\begin{document}
			blabla
			\end{document}
* always have to save (compilation works on files)
* work in WYCIWYG mode: 
	* What You Check Is What You Get
	* e.g. using [TeXShop](https://pages.uoregon.edu/koch/texshop/) or...
---

## Learning LaTeX

* https://latex-tutorial.com ?
* [LaTeX Primer](https://www.tug.org/twg/mactex/tutorials/ltxprimer-1.0.pdf) or at [wikibooks](https://en.wikibooks.org/wiki/LaTeX)
* Books including online books
* StackOverflow questions
	* Copy and paste source!
---

## (La)TeX beyond PDF

- In Jupyter Notebooks (language for all formulæ)
- The widespread standard for denoting math symbols
	- works kind of for Word even
- [MathJax](https://www.mathjax.org/) within web-pages
- The Beamer format to create slides
- [MathLive Web Component](https://cortexjs.io/mathlive/)
- Wikipedia...
- Catcodes: characters make macros
- Just do it online? several tools Overleaf, FidusWriter, ...
- ...
---

## The IU template 

* Idea: Multipage document
* One checkout
	* or download
* Includes a references' system
	* uses BiBTeX
* See here: https://github.com/IUBH-IT-Technik-Profs-Sandbox/LaTeX-IUBH-Template
	* contributions welcome

