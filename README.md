# chemprog-autumn2017
Repo for course hometasks & lecture materials on "Programming foundations for chemistry problems solving" (in Russian)

## Additional materials and links

### python & common pythonish stuff

- [Awesome python](https://github.com/vinta/awesome-python) - list of awesome links (check it!). You can find there different materials on topics like: python code optimization, debugging, etc.

- [STA 663: Computational Statistics and Statistical Computing](http://people.duke.edu/~ccc14/sta-663-2017/) - advansed course on python, with introduction to many useful libraries and methods you all should read about =)

- [A gallery of interesting Jupyter Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)

### Algorithms

- [e-maxx.ru](https://e-maxx.ru/algo/) - Russian-speaking site with algorithm explanations

### Data science, machine learning and related

- [Machine learning list from Academic University course](https://github.com/demidovakatya/vvedenie-mashinnoe-obuchenie)

- [Oxford NLP course materials](https://github.com/oxford-cs-deepnlp-2017/lectures)

- [Introductory book to Bayesan statistics with Python and PyMC3](https://github.com/aloctavodia/Statistical-Rethinking-with-Python-and-PyMC3)

### Structural bioinformatics & chemoinformatics packages & tools
This list includes collection of python packages and tools related to structural bioinformatics, chemoinformatics and chemistry you should be familiar with, we want to mention them all during this course :) 

#### Database 

- [bioservices](https://pythonhosted.org/bioservices/) - python package to access biological databases (provides similar API to several databases, including KEGG and Uniprot).

- [PyPDB github repo](https://github.com/williamgilpin/pypdb) - In most cases when you work with RSCB.org, you need only one thing - a particular protein structure. All widely used packages include implementation for method to get this structure by PDB identifier. But what if you want to make more complex requests? But what if you want to query all antibodies with both heavy and light chains, found in specific mammalian species, and you don't know their identifiers yet? This package provides full interface for RCSB Rest API, which allows to build complex queries like that, and that's why I like it :)

#### Protein structures manipulation

- [BioPython](http://biopython.org) - this is well-known bioinformatics package. includes some tools for structural bioinformatics (in particular, PDB file reader), but sometimes may be buggy. This is build on top on numpy/scipy.

- [ProDy](http://prody.csb.pitt.edu/) - this tool provides better interface to work with PDB files than biopython. It also has some visualization capabilities, but they are quite specific. Also check other packages which can be obtained from that page.

#### Protein structures visualizations
- [WebGL based protein viewer](https://github.com/arose/ngl) - awesome stuff! Might be hard to install. Adds a powerfull and shiny protein viewer to your IPython notebooks. 

- [PyMOL](http://pymol.org) - all-in-one tool, everyone who works with protein structures uses something like this. Supports scripting in python-like DSL. It is made with python & C++. Supports plugins.

- [rdkit](https://github.com/rdkit/rdkit) and related materials/tutorial from [RDKit User Group Meeting 2016](https://github.com/rdkit/UGM_2016)

