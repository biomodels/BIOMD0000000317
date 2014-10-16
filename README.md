# BIOMD0000000317: shenorr02

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000317.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000317.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000317 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the single input module, SIM, described in the article:  
**Network motifs in the transcriptional regulation network of Escherichia coli**   
Shai S. Shen-Orr, Ron Milo, Shmoolik Mangan, Uri Alon, _Nat Genet_ 2002
31:64-68; PMID:[11967538](http://www.ncbi.nlm.nih.gov/pubmed/11967538);
DOI:[10.1038/ng881](http://dx.doi.org/10.1038/ng881);

Abstract:  
Little is known about the design principles of transcriptional regulation
networks that control gene expression in cells. Recent advances in data
collection and analysis, however, are generating unprecedented amounts of
information about gene regulation networks. To understand these complex wiring
diagrams, we sought to break down such networks into basic building blocks. We
generalize the notion of motifs, widely used for sequence analysis, to the
level of networks. We define 'network motifs' as patterns of interconnections
that recur in many different parts of a network at frequencies much higher
than those found in randomized networks. We applied new algorithms for
systematically detecting network motifs to one of the best-characterized
regulation networks, that of direct transcriptional interactions in
Escherichia coli. We find that much of the network is composed of repeated
appearances of three highly significant motifs. Each network motif has a
specific function in determining gene expression, such as generating temporal
expression programs and governing the responses to fluctuating external
signals. The motif structure also allows an easily interpretable view of the
entire known transcriptional network of the organism. This approach may help
define the basic computational elements of other biological networks.

This model reproduces the SIM timecourse presented in Figure 2b. All species
and parameters in the model are dimensionless.


