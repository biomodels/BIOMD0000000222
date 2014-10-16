# BIOMD0000000222: Singh2006_TCA_Ecoli_glucose

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000222.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000222.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000222 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Kinetic modeling of tricarboxylic acid cycle and glyoxylate bypass in Mycobacterium tuberculosis, and its application to assessment of drugtargets.**   
Singh VK , Ghosh I _Theor Biol Med Model_ 2006 Aug 3;3:27
[16887020](http://www.ncbi.nlm.nih.gov/pubmed/16887020) ,  
**Abstract:**   
BACKGROUND: Targeting persistent tubercule bacilli has become an important
challenge in the development of anti-tuberculous drugs. As the glyoxylate
bypass is essential for persistent bacilli, interference with it holds the
potential for designing new antibacterial drugs. We have developed kinetic
models of the tricarboxylic acid cycle and glyoxylate bypass in Escherichia
coli and Mycobacterium tuberculosis, and studied the effects of inhibition of
various enzymes in the M. tuberculosis model. RESULTS: We used E. coli to
validate the pathway-modeling protocol and showed that changes in metabolic
flux can be estimated from gene expression data. The M. tuberculosis model
reproduced the observation that deletion of one of the two isocitrate lyase
genes has little effect on bacterial growth in macrophages, but deletion of
both genes leads to the elimination of the bacilli from the lungs. It also
substantiated the inhibition of isocitrate lyases by 3-nitropropionate. On the
basis of our simulation studies, we propose that: (i) fractional inactivation
of both isocitrate dehydrogenase 1 and isocitrate dehydrogenase 2 is required
for a flux through the glyoxylate bypass in persistent mycobacteria; and (ii)
increasing the amountof active isocitrate dehydrogenases can stop the flux
through the glyoxylate bypass, so the kinase that inactivates isocitrate
dehydrogenase 1 and/or the proposed inactivator of isocitrate dehydrogenase 2
is a potential target for drugs against persistent mycobacteria. In addition,
competitive inhibition of isocitrate lyases along with a reduction in the
inactivation of isocitrate dehydrogenases appears to be a feasible strategy
for targeting persistent mycobacteria. CONCLUSION: We used kinetic modeling of
biochemical pathways to assess various potential anti-tuberculous drug targets
that interfere with the glyoxylate bypass flux, and indicated the type of
inhibition needed to eliminate the pathogen. The advantage of such an approach
to the assessment of drug targets is that it facilitates the study of systemic
effect(s) of the modulation of the target enzyme(s) in the cellular
environment.

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


