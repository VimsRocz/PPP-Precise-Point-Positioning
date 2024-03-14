# PPP-Precise-Point-Positioning
# Precise Point Positioning (PPP) Analysis

### Format of data is most important so please arange your data in such format to run MATLAB file


## Introduction
Precise Point Positioning (PPP) is an advanced technique for absolute positioning using Global Navigation Satellite Systems (GNSS) with a single receiver. This approach relies on precise satellite orbit and clock information to achieve centimeter-level positioning accuracy. In this project, we process 4 hours of observation data from a Javad receiver using PPP and investigate the accuracy and precision of the results.

## Tasks

### 1. Determination of Antenna Position with PPP Method
#### a. Satellite Usage and DOP Values
Plot and discuss the number of used satellites and the Dilution of Precision (DOP) values.

#### b. Design Matrix Setup
Explain the setup of the design matrix for PPP in static and kinematic modes. Discuss why a single epoch PPP solution is not feasible.

#### c. Stochastic Model Setup
Set up the stochastic model with elevation-dependent weighting.

#### d. Coordinate Solution with One-Step LSA Approach
Compute the coordinate solution for static and kinematic modes using the one-step Least Squares Adjustment (LSA) approach.

#### e. Coordinate Solution with Pre-elimination/Back-substitution LSA Approach
Compute the coordinate solution for static and kinematic modes using the pre-elimination/back-substitution LSA approach.

### 2. Visualization of Static and Kinematic Coordinate Solutions
Plot static and kinematic coordinate solutions in a topocentric coordinate system versus time and as a 2D 'Scatter' figure. Compute mean, root-mean-square errors, and empirical standard deviation for kinematic mode. Evaluate the results.

### 3. Formal Standard Deviation Calculation
Compute the formal standard deviation of the estimated coordinates in the topocentric coordinate system for static and kinematic modes.

### 4. Visualization of Other Estimated Parameters
Plot other estimated parameters and discuss the fixability of ambiguities to an integer.

### 5. Plotting Code and Phase Residuals
Plot code and phase residuals with respect to satellite elevation.

### 6. Identical Standard Deviation Comparison
Investigate the effects of using identical standard deviations for code and carrier phase for the kinematic time series. Compute, plot, and discuss all parameters.

## Conclusion
Summarize the findings and conclusions drawn from the PPP analysis, highlighting key insights and potential areas for further research.

