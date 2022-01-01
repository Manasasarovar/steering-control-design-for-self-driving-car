# steering-control-design-for-self-driving-car
# Introduction
Recently, there have been significant improvements in vehicle technologies. Along with a
development, various researches are still in progress to overcome existing obstacles.
Autonomous vehicles are being tested under the real road conditions, and similar ongoing
challenges such as DARPA [1] encourage development of advanced technologies. In detail,
performing numerous experiments is crucial to adapt a new technology into the real world
after buildup process. Throughout the field test, it can be analyzed to see the difference
whether the method shows enhancement or not, compared to existing functions.

# A discrete time Linear Quadratic Regulator (LQR) for a self-driving car steering system
he following concepts central to control theory and controller design.

1) PID Control
2) LQR Control
3) Discrete and Continuous Control
4) Laplace and Z Domain
5) Discretization Methods: Step Invariance, Impulse Invariance, Zero Order Hold (ZOH) etc.
6) Samping and Pole Zero Matching
7) Linear Quadratic Integration (LQI) Control

# Overtake maneuver strategy allows a smart vehicle (an independent agent), to safely overtake the vehicles ahead of it by taking decisions based on the belief/knowledge it has about its environment.

This demo showcases a Simulink model architecture for creating and simulating synthetic scenarios. It reads as input the scenario file saved using the Driving Scenario Designer (DSD) application. This architecture allows creation of synthetic scenarios, by:

# Marking an actor in the scenario as an autonomous smart actor.
Installing car-following (driver) model on some of the actors.
Introducing rogue actors (actors devoid of any intelligence) in the scenario.
Driving scenario designer (DSD) application is part of Automated Driving System Toolbox (ADST). Refer to the documentation here for more information.

Configuration parameters can be set for individual actors to observe the variations in the behavior. The plan algorithm in the smart actor supports overtake maneuver on straight road.

# MATLAB Toolbox dependencies
This model has been tested with MATLAB R2019b. The version tested with MATLAB R2018b and R2019a is available with release tag v1.0-MATLAB19a.

To run this model, you need: MATLAB, Automated Driving System Toolbox (ADST), Model Predictive Control Toolbox, Simulink, Simulink Coder, and Stateflow.

Running the model
The model needs a scenario file saved using the DSD application. A sample scenario file scenarioInput.mat is already included in the repository.

Run the Simulink model mOvertakeManeuver.slx and see the visualization.

Further documentation
See the file Overtake-Maneuver.pdf for detailed documentation covering - Scenario description, new scenario generation, Simulink model description, configuration and scenario visualization.
