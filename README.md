# RegressionSensitivityAnalysisR
A simple script to run a Monty Carlo simulation to test the sensitivity of a variable in a linear regression to random error assocaited with the measurment of that variable. This script is related to a paper published in ___________ examing the relationship between molecular weight, chemical composition, and radiocarbon age of high molecular weight dissovled organic matter. It can be found at ___________. 

# Data Structure
This code expects a table of values where each row represents a sample or datapoint for a regression. Then it expects 3 columns; "HS" is the x-variable and denotes the relative humic substances content of the sample. C14 and C13 are the y-variables and are the radiocarbon and stable carbon isotope content of the samples.

# Notes
Runtime for the code is controlled by the number of simulations run (n = 5000 is default but can be changed) and the number of relative error levels desired (currently the script runs 0-35% relative error in 2.5% error increments).
