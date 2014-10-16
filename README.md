# MODEL7519354389: Zou2007_MAPK_SignalingNetworks

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL7519354389.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL7519354389.git@20140916`

## Usage

Importing the model package.

`import MODEL7519354389 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Modeling specificity in the yeast MAPK signaling networks**   
Zou X, Peng T, Pan Z _J. Theor. Biol._ (2008);250(1):139-55
[17977559](http://www.ncbi.nlm.nih.gov/pubmed/17977559 ) ,  
**Abstract:**   
Cells sense several kinds of stimuli and trigger corresponding responses
through signaling pathways. As a result, cells must process and integrate
multiple signals in parallel to maintain specificity and avoid erroneous
cross-talk. In this study, we focus our theoretical effort on understanding
specificity of a model network system in yeast, Saccharomyces cerevisiae,
which contains three mitogen-activated protein kinase (MAPK) signal
transduction cascades that share multiple signaling components. The cellular
response to the pheromone, the filamentous growth and osmotic pressure stimuli
in yeast is described and an integrative mathematical model for the three MAPK
cascades is developed using available literature and experimental data. The
theoretical framework for analyzing the specificity of signaling networks
[Bardwell, L., Zou, X.F., Nie, Q., Komarova, N.L., 2007. Mathematical models
of specificity in cell signaling. Biophys. J. 92, 3425-3441] is extended to
include multiple interacting pathways with shared components. Simulations are
also performed with any one stimulus, with any two simultaneous stimuli, and
with the simultaneous application of the three stimuli. The interactions
between the three pathways are systematically investigated. Moreover, the
specificity and fidelity of this model system are calculated using our newly
developed concept under different stimuli or with specific mutants. Our
simulated and calculated results demonstrate that the yeast MAPK signaling
network can achieve specificity and fidelity by filtering out spurious cross-
talk between the relevant pathways through different mechanisms, such as
scaffolding, cross-inhibiting, and feedback control. Proof that Pbs2 and Hog1
are essential for the maintenance of signaling specificity is presented. Our
studies provide novel insights into integration of relevant signaling pathways
in a biological system and the mechanisms conferring specificity in cellular
signaling networks.

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


