# Bayesian_inference-for-Low-Cycle-Fatigue-Analysis

This repository proceeds to the implementation of a bayesian inference process under a Fatigue Life Analysis framework. Fatigue Life, or the theoretical time limit after which a piece of mechanic will break 
is central to mechanical engineering. Here the paper explores the influence of notches on the pieces of artefact and the piece structure over the total estimated life.
The model relies on a parameter calibration process of one parameter of the Weibull distribution used to represent the microscopic risk of break occurrence, in order not to 
be hindered from scarce data.   
The goal of this repository is to implement the bayesian inference part using the pymc3 library and a custom likelihood function. 
This is part of a larger work but can be presented independenly as the statistical process does not depend, except for parametrization on the other parts. 

