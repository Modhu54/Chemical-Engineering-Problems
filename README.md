Chemical Reactor Modeling and Control using Python

This repository contains Python implementations of solved problems related to chemical reactor modeling, dynamic simulation, and process control. The programs demonstrate the application of mathematical modeling, numerical methods, and classical control techniques for analyzing the behavior of batch and continuous stirred tank reactors (CSTR). The repository currently includes the following topics:

Batch Reactor with PI Controller
CSTR Reactor – Dynamic Response
CSTR Reactor – Heat Generation and Removal
CSTR Reactor – Multiplicities in Reactor Temperature and Concentration
PI Controller Application in CSTR
CSTR Reactor – Dynamic Response Using Initial Value Problem (IVP) Method

1. Batch Reactor Mathematical Modeling and Control

This project develops a mathematical model and dynamic simulation of a batch reactor undergoing consecutive reactions (A → B → C). The model is based on mass and energy balance equations coupled with Arrhenius reaction kinetics. Product B is the desired intermediate, and the optimal batch time is determined to maximize its yield while minimizing by-product C formation. A conventional Proportional–Integral (PI) controller is implemented to regulate reactor temperature by manipulating steam heating and cooling-water flow. The study investigates the closed-loop dynamic response of the reactor, temperature trajectory tracking, and process performance. In addition, the mathematical modeling of a semi-batch reactor is included to compare operating strategies and reactor behavior.

2. CSTR Reactor – Dynamic Response

This program develops a dynamic model of a non-isothermal Continuous Stirred Tank Reactor (CSTR) based on mass and energy balance equations. The reactor behavior is simulated for an irreversible first-order exothermic reaction using numerical integration. Dynamic responses to disturbances, such as changes in feed temperature, are analyzed to study transient reactor performance. The simulation provides insight into concentration and temperature evolution under open-loop operating conditions.

3. CSTR Reactor – Dynamic Response Using Initial Value Problem (IVP) Method

This program simulates the transient behavior of a non-isothermal CSTR by solving the governing mass and energy balance equations as an initial value problem (IVP). The reactor dynamics are obtained using Python's numerical ODE solvers, allowing the evolution of reactant concentration and reactor temperature to be analyzed over time. The implementation provides an efficient and accurate alternative to conventional integration methods for studying transient reactor behavior under specified initial conditions.


4. CSTR Reactor – Heat Generation and Removal

This program analyzes the thermal behavior of a non-isothermal CSTR by computing heat generation and heat removal as functions of reactor temperature. The intersection of these curves identifies the reactor steady-state operating points. The simulation demonstrates the existence of stable and unstable steady states, highlighting the importance of thermal balance in reactor operation and safety.

5. CSTR Reactor – Multiplicities in Reactor Temperature and Concentration

This program investigates steady-state multiplicity and hysteresis behavior in a non-isothermal CSTR. By varying the coolant jacket temperature, the corresponding reactor temperature and reactant concentration are determined to generate multiplicity curves. The results illustrate ignition-extinction phenomena and distinguish stable and unstable operating regions, providing a deeper understanding of nonlinear reactor characteristics.

6. PI Controller Application in CSTR

This program implements a classical Proportional–Integral (PI) controller to regulate the temperature of a non-isothermal CSTR. The controller manipulates the coolant jacket temperature to maintain the desired reactor temperature, including operation near an unstable steady state. Closed-loop simulations evaluate set-point tracking, controller performance, and reactor stability under varying operating conditions.



