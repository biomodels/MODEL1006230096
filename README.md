# MODEL1006230096: Cloutier2009_EnergyMetabolism_ModelF

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230096.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230096.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230096 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**The control systems structures of energy metabolism.**   
Cloutier M, Wellstead P. _J R Soc Interface_ 2010 Apr 6;7(45):651-65
[19828503](http://www.ncbi.nlm.nih.gov/pubmed/19828503) ,  
**Abstract:**   
The biochemical regulation of energy metabolism (EM) allows cells to modulate
their energetic output depending on available substrates and requirements. To
this end, numerous biomolecular mechanisms exist that allow the sensing of the
energetic state and corresponding adjustment of enzymatic reaction rates. This
regulation is known to induce dynamic systems properties such as oscillations
or perfect adaptation. Although the various mechanisms of energy regulation
have been studied in detail from many angles at the experimental and
theoretical levels, no framework is available for the systematic analysis of
EM from a control systems perspective. In this study, we have used principles
well known in control to clarify the basic system features that govern EM. The
major result is a subdivision of the biomolecular mechanisms of energy
regulation in terms of widely used engineering control mechanisms:
proportional, integral, derivative control, and structures: feedback, cascade
and feed-forward control. Evidence for each mechanism and structure is
demonstrated and the implications for systems properties are shown through
simulations. As the equivalence between biological systems and control
components presented here is generic, it is also hypothesized that our work
could eventually have an applicability that is much wider than the focus of
the current study.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Cloutier M, Wellstead P. (2009) - version=1.0**
](http://models.cellml.org/exposure/1298e7f3cdd664d79ac289b591126ab5)  
The original CellML model was created by:  
**Catherine Lloyd**   
c.lloyd@auckland.ac.nz  
The University of Auckland  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


