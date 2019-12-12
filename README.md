# Subsystem 2: Optimising Paddle 

Author: Gabriele D'Amone

## Dependencies

This subsystem runs using Matlab R2019b.

The packages used by this subsystem are listed in the repository requirements.txt. Please refer there to manually install required packages.

## Getting Started

To run this code, first ensure you have installed on Matlab the following Toolboxes:

- Optimisation Toolbox
- Global Optimisation Toolbox
- Curve Fitting Toolbox

Then, please find below an overview of the Matlab files and their content:

- **Airfoil2.m** Linear Programmatic Fitting to determine the equations for Coefficient of Drag and Coefficient of Lift
  - Download **Coefficient.xlsx**
- **Fatigue.m** Linear Programmatic Fitting to output Force Profile affected by Fatigue
- **UpdatedFunctionTwoVariables.m** Fmincon Interior Point Algorithm
- **SQPAlgorithm.m** Fmincon Sequential Quadratic Programming Algorithm



## Performance

This subsystems code was developed **up to Friday, December 15th**, on a HP running Windows 10 with the following specifications:

| Processor Name: Intel Core i7 | Processor Speed: 2.6 GHz | Number of Processors: 1 | Total Number of Cores: 8

Execution time is noted at the end of the Matlab output. Last run time was approximately 3 seconds.

The code was developed **from Monday, December 19th**, on an MSI Laptop running Windows 10.0.1 with the following specifications:

| Processor Name: Intel Core i7 | Processor Speed: 2.6 GHz | Number of Processors: 1 | Total Number of Cores: 4
