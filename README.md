# BIOMD0000000028: model_0000001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000028.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000028.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000028 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


The model corresponds to the schema 3 of Markevich et al 2004, as described in
the figure 2 and the supplementary table S2. Phosphorylations follow
distributive random kinetics, while dephosphorylations follow an ordered
mechanism. The phosphorylations are modeled with three elementary reactions:  
E+S<=>ES->E+P  
The dephosphorylations are modeled with five elementary reactions:  
E+S<=>ES->EP<=>E+P  
The model reproduces figure 5 in the main article.

The model is further described in:  
**Signaling switches and bistability arising from multisite phosphorylation in protein kinase cascades.** Markevich NI, Hoek JB, Kholodenko BN. J Cell Biol. 2004 Feb 2;164(3):353-9.   
PMID: [14744999](http://www.ncbi.nlm.nih.gov/pubmed/14744999) ; DOI:
[10.1083/jcb.200308060](http://dx.doi.org/10.1083/jcb.200308060)  
Abstract:  
Mitogen-activated protein kinase (MAPK) cascades can operate as bistable
switches residing in either of two different stable states. MAPK cascades are
often embedded in positive feedback loops, which are considered to be a
prerequisite for bistable behavior. Here we demonstrate that in the absence of
any imposed feedback regulation, bistability and hysteresis can arise solely
from a distributive kinetic mechanism of the two-site MAPK phosphorylation and
dephosphorylation. Importantly, the reported kinetic properties of the kinase
(MEK) and phosphatase (MKP3) of extracellular signal-regulated kinase (ERK)
fulfill the essential requirements for generating a bistable switch at a
single MAPK cascade level. Likewise, a cycle where multisite phosphorylations
are performed by different kinases, but dephosphorylation reactions are
catalyzed by the same phosphatase, can also exhibit bistability and
hysteresis. Hence, bistability induced by multisite covalent modification may
be a widespread mechanism of the control of protein activity.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2010 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


