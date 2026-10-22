# RegressionSensitivityAnalysisR
A simple script to run a Monty Carlo simulation to test the sensitivity of a variable in a linear regression to random error associated with the measurement of that variable. This script is related to a paper published in ___________ examining the relationship between molecular weight, chemical composition, and radiocarbon age of high molecular weight dissolved organic matter. It can be found at ___________. This work is based on work by Walker et al. (2016, Nature Geoscience).

# Data Structure
This code expects a table of values where each row represents a sample or data point for a regression. Then it expects 3 columns; "HS" is the x-variable and denotes the relative humic substances content of the sample. C14 and C13 are the y-variables and are the radiocarbon and stable carbon isotope content of the samples.

# Notes
Runtime for the code is controlled by the number of simulations run (n = 5000 is default but can be changed) and the number of relative error levels desired (currently the script runs 0-35% relative error in 2.5% error increments).

# License
MIT

# Relevant References
Walker, B. D., Beaupré, S. R., Guilderson, T. P., McCarthy, M. D. & Druffel, E. R. M. Pacific carbon cycling constrained by organic matter size, age and composition relationships. Nat. Geosci. 9, 888–891 (2016) doi:10.1038/ngeo2830.
