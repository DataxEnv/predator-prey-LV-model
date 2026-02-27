# predator-prey Model Under the Lotka-Volterra (LV) System. 
Predator-Prey dynamics is one of the simplest non-linear ecological systems. The **Lotka-Volterra (LV)** framework provides a minimal mathematical representation of these interactions. It expresses population change as a set of **coupled differential equation**.


## The Conceptual Model
The conceptual model defines the interacting variables and directional processes. The system is reduced to two populations: **Prey (N)**, and **Predator (P)**. Prey reproduce, predators consume prey, and predators experience mortality. This isolates the *essential* dynamics prior to the mathematical representation.

![WhatsApp Image 2026-02-27 at 3 17 56 AM](https://github.com/user-attachments/assets/89ac89c1-531c-413f-8d47-c1ef447ceb4f)
 
   Figure 1: Structural representation of predator-prey interaction. source: Author.

  ## The Mathematical Model
  The Lotka-Volterra equation describes the temporal dynamics of the system:

*dN/dt = rN - aNP*

*dP/dt = bNP - mP*

where:  
* N: prey population
* P: predator population
* r: intrinsic growth rate of prey
* a: predation rate coefficient
* b: conversion efficiency of consumed prey into predator reproduction
* m: predator mortality rate

## The Simulation
The coupled differential equations are Numerically integrated to observe the system dynamics over time.

![WhatsApp Image 2026-02-27 at 3 17 56 AM](https://github.com/user-attachments/assets/89ac89c1-531c-413f-8d47-c1ef447ceb4f)

Figure 2: Simulated Predator-prey osillations generated from the LV system.
