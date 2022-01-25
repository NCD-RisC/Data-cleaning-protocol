# Example of detection of implausible values using Mahalanobis distance

Mahalanobis_detection.R: 

function mahalanobis_plot takes two numerical vector of the same size and a level of detection, and retrurns a density scatter plot with the individual detected circled in red, and a vector with the position of the identified individuals
Assumes that the input data a bivariate normally distributed

example_maha.R: 

Illustrate the above function on simulated data 

