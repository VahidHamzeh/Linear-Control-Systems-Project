![Control](https://img.shields.io/badge/Strategy-Active_Control-blue?style=for-the-badge&logo=mathworks&logoColor=white)
![Model](https://img.shields.io/badge/System-Quarter--Car-red?style=for-the-badge&logo=automotive&logoColor=white)
![Analysis](https://img.shields.io/badge/Method-Disturbance_Rejection-orange?style=for-the-badge&logo=scikit-learn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=github&logoColor=white)

# Active Suspension System Design - Quarter-car Model

## 👥 Team Members
* **Amirali Fazeli** ([@amiralitw9](https://github.com/amiralitw9))
* **Vahid Hamzeh** ([@VahidHamzeh](https://github.com/VahidHamzeh))


## Project Overview
This project focuses on the modeling, analysis, and control system design of an active vehicle suspension system using a **Quarter-car Model**. The goal is to optimize the trade-off between **Ride Comfort** (minimizing cabin vibrations) and **Road Holding** (maintaining tire-road contact) by implementing an active control strategy.

## 🚗 Suspension System Comparison

To better understand the necessity of active control, we compare the mechanical behavior of passive, semi-active, and active suspension systems:

<img width="389" height="197" alt="Screenshot 1405-03-27 at 5 30 46 PM" src="https://github.com/user-attachments/assets/e621b934-59d7-4ec1-86da-b8d19ec2b6bc" />

* **Passive Suspension:** Relies solely on springs and dampers to absorb energy. It is fixed and cannot adapt to varying road conditions.
* **Active Suspension:** Uses an external energy source (actuator) to adjust the suspension force in real-time, significantly improving the trade-off between ride comfort and road holding.

## Key Objectives
- **Dynamic Modeling:** Derivation of system equations of motion and state-space representation.
- **Controller Design:** Development of a robust PI controller for optimal path tracking and vibration isolation.
- **Disturbance Rejection:** Implementation of a Feedforward compensator to mitigate road disturbances based on DC-Gain matching.
- **Estimation:** Design of a Disturbance Estimator for scenarios where direct road roughness measurement is unavailable.
- **Robustness Analysis:** Evaluation of system performance and stability against sensor noise and physical parameter variations (e.g., spring stiffness degradation).

## Repository Structure
- `/Simulations`: Contains all MATLAB/Simulink models and simulation scripts.
- `/Report`: The final project documentation including detailed mathematical derivations and analysis results.

## Technical Details
- **System Model:** Quarter-car passive-active suspension dynamics.
- **Control Strategy:** PI control, Feedforward compensation, and Disturbance Estimation.
- **Analysis Tools:** MATLAB & Simulink.
---
*Developed for Linear Control Systems Course | Sharif University of Technology*
