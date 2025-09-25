# Modeling_and_Simulation_for_DC_Motor

## 🔹 Abstract
This project focuses on modeling, simulation, and control of a DC motor system.  
The motor’s electrical and mechanical parameters were estimated through experimental testing and simulation. **MATLAB/Simulink** was used to develop a mathematical model and verify motor dynamics.  
A **PID controller** was designed and tuned to regulate motor speed using PWM signals.  
The control algorithm was implemented in **C++** and tested on hardware.  
Verification was performed using **Proteus simulation** and **SerialPlot visualization**, ensuring consistency between theoretical modeling and real-world performance.

---

## 🔹 Block Diagram (Conceptual Flow)

1. **MATLAB/Simulink Modeling** → Build motor equations & simulate open-loop response.  
2. **Parameter Estimation** → Extract motor parameters:  
   - Armature Resistance \( R_a \)  
   - Armature Inductance \( L_a \)  
   - Torque Constant \( K_t \)  
   - Back EMF Constant \( K_e \)  
   - Rotor Inertia \( J \)  
   - Viscous Friction \( B \)  
   using curve fitting & response analysis.  
3. **PID Controller Design** → Tune \( K_p, K_i, K_d \) for stable speed regulation.  
4. **C++ Implementation** → Code PWM control & sensor feedback on hardware.  
5. **Hardware-in-the-Loop (HIL)** → Test system with real motor and compare with model.  
6. **Verification** → Use **Proteus + SerialPlot** for visualization and validation.  

---

## 🔹 Tools & Technologies
- MATLAB/Simulink  
- C++  
- Proteus  
- SerialPlot  

---

## 🔹 Results
Verification using Proteus and SerialPlot:

![DC Motor Simulation](DC%20motor%20modeling%20and%20simulation_1.png)

The mathematical model of the DC motor using Matlab and Simulink:

![DC Motor Simulation](DC%20motor%20modeling%20andsimulation_2.png)
