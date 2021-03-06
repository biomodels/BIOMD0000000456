# BIOMD0000000456: MODEL1305030002

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000456.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000456.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000456 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Smallbone2013 - Metabolic Control Analysis - Example 3

Metabolic control analysis (MCA) is a biochemical formalism, defining how
variables, such as fluxes and concentrations, depend on network parameters. In
this paper, owing to its limitations, it is shown with three example models
(MODEL1305030000-2) that the algorithm with slight modification can be applied
to all models.

This model is described in the article:

[Metabolic Control Analysis: Rereading
Reder](http://identifiers.org/arxiv/1305.6449)

Kieran Smallbone

Quantitative Methods; Tue, 28 May 2013.

Abstract:

Metabolic control analysis is a biochemical formalism defined by Kacser and
Burns in 1973, and given firm mathematical basis by Reder in 1988. The
algorithm defined by Reder for calculating the control matrices is still used
by software programs today, but is only valid for some biochemical models. We
show that, with slight modification, the algorithm may be applied to all
models.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1305030000](http://identifiers.org/biomodels.db/MODEL1305030000) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


