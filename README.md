# Formal Methods for System Verification - Project: Non-Repudiation Protocol

![image](https://github.com/user-attachments/assets/831dcc12-d2d9-4814-b2ec-80a7af347f3d)

## Authors
- Andrea Munarin  
- Francesco Perencin  
- Simone Jovon  

## University
Ca' Foscari University of Venice  
Master's Degree Program, First Year  

---

## Project Objective
The goal of this project is to apply **stochastic modeling techniques** to analyze and model a **Non-Repudiation Protocol**. This work is part of the course on Formal Methods for System Verification. 

The project is conducted as **Group 7** and involves the use of the **PEPA stochastic process algebra** for modeling and verification tasks.

---

## Overview

### Problem Description
A **Non-Repudiation Protocol** ensures that neither the sender nor the receiver of a message can deny their participation in the communication process. This is crucial in secure communications, particularly in digital contracts, e-commerce, and other sensitive transactions.

Our goal is to model and verify the behavior of such a protocol using stochastic methods. Specifically, we aim to:
- Represent the protocol components and their interactions.
- Analyze system performance and derive key measures such as steady-state probabilities, throughput, and utilization.

### Steps Taken
The project followed these main steps:
1. **Introduction**  
   Informally and carefully described the **Non-Repudiation Protocol**, highlighting the problem it addresses and its relevance.

2. **System Analysis**  
   Identified key components of the protocol and their activities, both individual and cooperative.

3. **Behavioral Description**  
   Explained how components interact and behave within the system.

4. **High-Level Representation**  
   Modeled each component using **PEPA stochastic process algebra**.

5. **System Composition**  
   Defined the overall system as a combination of the interacting components in PEPA.

6. **Derivation Graph**  
   Constructed a derivation graph to visualize the system states and transitions.

7. **Infinitesimal Generator Matrix (Q)**  
   Derived the infinitesimal generator matrix \( Q \) representing the underlying Markov process.

8. **Quantities of Interest**  
   Identified and expressed key performance metrics:
   - Steady-state probabilities.
   - System throughput.
   - Utilization of specific components.
   - Expected response times.

9. **Simulation and Evaluation**  
   Encoded the system in the **PEPA Eclipse Plug-in** and evaluated performance metrics.

---

## Zhou & Gollmann Model Representation
The **Zhou & Gollmann Model** of the Non-Repudiation Protocol will be included here, detailing the specific components, interactions, and stochastic properties.

![image](https://github.com/user-attachments/assets/a1ec06ab-f5d0-4ae8-ad37-e1086ef4262d)


---

## Derivation Graph
The derivation graph of the modeled system visualizes the transitions between different system states. It provides insights into system dynamics and behavior under varying conditions.

![image](https://github.com/user-attachments/assets/32483f52-a84c-4de2-b969-477ab3777af4)


---

## Results and Conclusion
The project successfully modeled and verified a Non-Repudiation Protocol using stochastic methods. Through the PEPA toolset, we analyzed the protocol's behavior and derived meaningful insights into its performance metrics.

---

## Tools and Resources
- **PEPA Eclipse Plug-in**  
  Used for system modeling, analysis, and evaluation.

- **References**  
  - Jane Hillston, *A Compositional Approach to Performance Modelling*.  
  - Zhou & Gollmann, *A Fair Non-Repudiation Protocol*.  

---

## How to Use This Repository
1. Clone the repository to your local machine.  
2. Open the PEPA Eclipse project file to view and modify the model.  
3. Explore the included graphs, \( Q \)-matrix, and simulation results.  

---

## License
This project is for educational purposes as part of the Master's program at Ca' Foscari University. All rights reserved by the authors.
