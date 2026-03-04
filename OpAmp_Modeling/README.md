# Operational Amplifier Circuits in Simscape

This repository contains Simscape/Simulink implementations for modeling electrical circuits using Operational Amplifiers (Op-Amps). These exercises were developed for the **Mechatronics** course.

## Exercise 2.4: Op-Amp Arithmetic & D/A Converter
This exercise focuses on using Op-Amps for mathematical operations and signal conversion. 

* **Analog Arithmetic:** The first section requires designing a circuit with the minimum number of operational amplifiers to solve the linear equation $v_0 = 5v_1 + 3v_2 + 10v_3$.
* **Digital-to-Analog Conversion:** The second section implements and verifies a 4-Bit D/A (Digital-to-Analog) converter circuit.

### Simulation
<div align="center">
  <img src="Op-Amp Arithmetic Simulink.png" width="600" alt="Simulink Implementation of Op-Amp Arithmetic">
</div>

---

## Exercise 2.5: Active PI Controller
This exercise demonstrates how to implement a Proportional-Integral (PI) controller using an active Op-Amp circuit.

* **Dynamic Modeling:** It begins by obtaining the dynamic equations of the circuit to prove its PI behavior and establish the mathematical relationship between the proportional ($K_p$) and integral ($K_i$) gains.
* **Closed-Loop Control:** The circuit is then modified to compute the error signal (the difference between the reference and the plant's output) in a standard closed-loop architecture.
* **Plant Simulation:** Finally, the controller is tested alongside a first-order plant with the transfer function $G(s) = \frac{10}{0.5s+1}$. The circuit components used for this tuning are $R_i = 10k\Omega$, $R_f = 100k\Omega$, and $C = 10\mu F$.

### Simulation
<div align="center">
  <img src="PI Controller Simulink.png" width="600" alt="Simulink Implementation of the PI Controller">
</div>
