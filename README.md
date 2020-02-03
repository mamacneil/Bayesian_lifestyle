# Your Bayesian Lifestyle
## Getting started with Bayesian statistical models in R or Python

Material for this tutorial have been cribbed from Chris Fonnesbeck and Colin Carroll, the original contents of which can be found (here)[https://github.com/fonnesbeck/Bayes_Computing_Course.git]


## Material for course on Bayesian Computation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mamacneil/Bayesian_lifestyle/master)

## Setup

This tutorial assumes that you have [Anaconda](https://www.anaconda.com/distribution/#download-section) (Python 3.6 or 3.7) setup and installed on your system. If you do not, please download and install Anaconda on your system before proceeding with the setup.

The next step is to clone or download the tutorial materials in this repository. If you are familiar with Git, run the clone command:

    git clone https://github.com/fonnesbeck/Bayes_Computing_Course.git

otherwise you can [download a zip file](https://github.com/fonnesbeck/Bayes_Computing_Course/archive/master.zip) of its contents, and unzip it on your computer.
***
The repository for this tutorial contains a file called `environment.yml` that includes a list of all the packages used for the tutorial. If you run:

    conda env create

from the main tutorial directory, it will create the environment for you and install all of the packages listed. This environment can be enabled using:

    conda activate bayes_course

Then, you can start **JupyterLab** to access the materials:

    jupyter lab

The binder link above should also provide a working environment.

## Course Outline

This is subject to change. I will seek input and try to accommodate digression where there is interest. Roughly, the first half of the course jumps right in with applied examples, then steps back to cover some of the theory behind Bayesian methods before going carefully through another applied case study. 

### Wednesday, February 8
1. **Basic Bayes** 9:00am - 12:00pm
	- Bayes formula
	- Likelihoods, Priors, and Posteriors
	- Radon, it's everywhere
	- IQ drugs, they're real
	- Phase-shifts, with fish

2. **Hierarchcial Models**  1:00pm - 4:00pm
    - Motivation and case studies
    - Partial pooling
    - Building hierarchical models
    - Parameterizations
    - Model checking

 
### Thursday, January 9

3. **The Bayesian Workflow**  9:00am - 12:00pm
    - Prior predictive checks
    - Iterating models
    - Posterior predictive checks
    - Using the model

4. **Your data** 1:00pm - 4:00pm
    - Questions relating to your own data
    - How to get started with your unique problem
    - Resources

