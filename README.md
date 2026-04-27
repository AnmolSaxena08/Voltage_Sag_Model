# Voltage_Sag_Model

[cite_start]This project provides a comprehensive analysis of **Voltage Sag Characterization (VSC)** and mitigation within power distribution networks using **MATLAB/Simulink**[cite: 364, 371]. [cite_start]Voltage sags—defined as a reduction in RMS voltage between **10% and 90%** of the nominal value lasting from half a cycle to one minute [cite: 362][cite_start]—are a critical Power Quality (PQ) challenge that can cause data loss and equipment damage in sensitive industrial facilities[cite: 363, 389].

### **Research Objectives & Methodology**
[cite_start]The study focuses on identifying leading sag parameters—**magnitude, duration, and phase-angle jumps**—to establish root causes and design effective mitigation strategies[cite: 365, 391]. Key areas of analysis include:
* [cite_start]**Sag Propagation:** Analyzing how sags transition across different voltage levels through transformer windings[cite: 366, 392].
* [cite_start]**System Impedance:** Utilizing the **Voltage Divider Model** to simplify the power system and calculate the voltage at the Point of Common Coupling ($V_{pcc}$) using source ($Z_s$) and fault ($Z_f$) impedances[cite: 369, 370]:
  $$V_{pcc} = V_s \times \frac{Z_f}{Z_s + Z_f}$$
* [cite_start]**Fault Impact:** Investigating the influence of fault resistance and transformer configurations on sag severity and the occurrence of multistage sags from unsynchronized protection relay mechanisms[cite: 367, 368, 394].

### **Simulation & Key Findings**
[cite_start]The simulation environment, built in **Simscape Electrical**, features an **11 kV, 30 MVA** source with a Delta/Wye transformer stepping down to **0.4 kV** for load analysis[cite: 372, 397]. 
* [cite_start]**Results:** Line-to-Line fault simulations demonstrated significant sags on faulted phases while the unfaulted phase experienced a slight voltage swell[cite: 378, 398]. 
* [cite_start]**Mitigation:** The project explores the implementation of a **Dynamic Voltage Restorer (DVR)**—a series-connected voltage source that injects compensatory voltage during sag events to maintain a stable supply[cite: 381, 382, 400].

[cite_start]This research is authored by **Anmol Saxena** at Galgotias College of Engineering and Technology[cite: 383, 401].
