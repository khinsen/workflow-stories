# Analyzing molecular simulations

## Goal

Understand the dynamics of proteins by extracting information from Molecular Dynamics trajectories.

## Input data

Molecular Dynamics trajectories for proteins in solution. These are routinely produced in the course of simulation-based research projects, using standard software. Unfortunately, they are rarely shared with other groups, and even much less published. However, research groups often re-use their own trajectories for several projects. For the purpose of this workflow, the trajectory is assumed given as a file on a computer in the lab.

Typical size of the input data: 100 MB to 10 GB.

File formats: several formats are in use. All are binary, and reasonably well documented.

## Workflow

Trajectory analysis requires a combination of standard procedures and computational methods developed specifically for a project. The development and evaluation of the project-specific methods represents the main effort. I use [Python](http://www.python.org/) scripts using the [Molecular Modeling Toolkit](http://dirac.cnrs-orleans.fr/MMTK/), a molecular simulation library written in Python. The latter also supplies implementations of the standard methods.

The workflow is an iteration of the following steps:
 1. Write or modify a Python script.
 2. Execute it and inspect its results.

## Results

The workflow produces two types of results for publication:

 - plots illustrating the behavior of the proteins
 - the Python scripts implemented the project-specific methods

## Computational tools

 - [Python](http://www.python.org/) extended by some widely used general-purpose scientific libraries:
     + [NumPy](http://www.numpy.org/)
     + [Scientific Python](http://dirac.cnrs-orleans.fr/plone/software/scientificpython/)
     + [matplotlib](http://matplotlib.org/)

 - [Molecular Modeling Toolkit](http://dirac.cnrs-orleans.fr/MMTK/)

 - [Git](https://git-scm.com/) for version control

 - [ActivePapers](http://www.activepapers.org/) for dependency management
