# Subsystem 2: Optimising Paddle 

<img align="right" src="https://github.com/gabrieledamone/DE4-OPT/blob/master/Paddle%20Subsystem%20Image.png" height="420" width="480">

**Author:** Gabriele D'Amone

**Overview:** This study aims to maximise the propulsive force that a paddler with a muscular strength of 125 N can generate in a specific amount of time (180 seconds).

The outputs of this Optimisation will suggest a personalised Paddle blade design and Paddling Tecnique:

**Paddling Tecnique**

- Peak Blade Velocity 
- Stroke Exit Angle
- Stroke Rate

**Paddle Blade Design**

- Blade Cross Section
- Blade Surface Area



## Dependencies

This subsystem runs using Matlab R2019b.

The packages used by this subsystem are listed in the repository requirements.txt. Please refer there to manually install required packages.

## Getting Started

To run this code, first ensure you have installed on Matlab the following Toolboxes:

- Optimisation Toolbox
- Global Optimisation Toolbox
- Curve Fitting Toolbox

Then, please find below an overview of the Matlab files and their content:

- **AirfoilCoefficient.m** Metamodel of equations for Coefficient of Drag and Coefficient of Lift
  - Download **Coefficient.xlsx**
- **Fatigue.m** Metamodel of Force Profile affected by Fatigue
- **FminconInteriorPoint.m** Fmincon Interior Point Algorithm + Global Search 
- **SQPAlgorithm.m** Fmincon Sequential Quadratic Programming Algorithm


## Performance

This subsystems code was developed **up to Friday, December 15th**, on a HP running Windows 10 with the following specifications:

| Processor Name: Intel Core i7 | Processor Speed: 2.6 GHz | Number of Processors: 1 | Total Number of Cores: 8

Execution time is noted at the end of the Matlab output. Last run time was approximately 3 seconds.

The code was developed **from Monday, December 19th**, on an MSI Laptop running Windows 10.0.1 with the following specifications:

| Processor Name: Intel Core i7 | Processor Speed: 2.6 GHz | Number of Processors: 1 | Total Number of Cores: 4
