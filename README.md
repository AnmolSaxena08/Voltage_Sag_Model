# Voltage_Sag_Model
This project offers a comprehensive analysis of voltage sag characterization and mitigation in power distribution networks using MATLAB and Simulink. By simulating various symmetrical and asymmetrical fault scenarios, the research identifies critical parameters such as sag magnitude, duration, and phase-angle jumps that impact the stability of sensitive industrial equipment. The study utilizes a theoretical voltage divider model to analyze sag propagation through transformer windings and evaluates the performance of a Dynamic Voltage Restorer as an effective solution for maintaining a stable voltage supply. Authored by Anmol Saxena at Galgotias College of Engineering and Technology, this work bridges the gap between theoretical power quality research and practical industrial simulation.


# Voltage Sag Characteristics & Mitigation in Power Distribution Systems
> [cite_start]**Authors:** Mr. Anmol Saxena, Dr. Richa, Dr. Rahul Vivek Purohit [cite: 58]

## 1. Project Overview
[cite_start]This project provides a comprehensive analysis of **Voltage Sag Characterization (VSC)** and mitigation in power distribution networks using **MATLAB and Simulink**[cite: 364, 469]. [cite_start]By simulating various symmetrical and asymmetrical fault scenarios, the research identifies critical parameters such as sag magnitude, duration, and phase-angle jumps that impact the stability of sensitive industrial equipment[cite: 362, 470]. 

[cite_start]The study utilizes a theoretical **voltage divider model** to analyze sag propagation through transformer windings and evaluates the performance of a **Dynamic Voltage Restorer (DVR)** as an effective solution for maintaining a stable voltage supply[cite: 427, 471].

## 2. Publication & Recognition
[cite_start]This work is based on academic research conducted at **Galgotias College of Engineering and Technology**[cite: 59, 472].
* [cite_start]**Research Paper:** "Voltage Sag Characteristics in Power Distribution Systems under Fault Conditions" [cite: 57, 473]
* [cite_start]**Institution:** Department of Electronics & Communication Engineering [cite: 448, 474]
* [cite_start]**Full Text:** [Link to PDF in /publication folder] [cite: 450, 475]
* [cite_start]**Certification:** Official recognition of publication from the institution [cite: 345, 476]

## 3. Technical Specifications
* [cite_start]**Software:** MATLAB, Simulink, Simscape Electrical [cite: 371, 477]
* [cite_start]**Source Configuration:** 11 kV, 30 MVA, 50 Hz three-phase voltage source [cite: 326, 478]
* [cite_start]**Transformer:** Delta/Wye configuration (11 kV/0.4 kV, 1 MVA) to study sag propagation [cite: 373, 479]
* [cite_start]**Fault Types:** Single-line-to-ground, Double-line-to-ground, Line-to-line, and Three-phase faults [cite: 376, 480]

## 4. Mathematical Model
[cite_start]The project utilizes the voltage divider rule to calculate the voltage at the **Point of Common Coupling (PCC)**[cite: 133, 329]:

$$V_{pcc} = V_s \times \frac{Z_f}{Z_s + Z_f}$$

## 5. Visual System Overview
[cite_start]To provide immediate technical context without needing MATLAB, key model architectures and waveforms are included below[cite: 281, 481]:

### **System Architecture**
![Simulink Model](visuals/simulink_model.png)
[cite_start]*Figure: Complete Simulink block diagram for the 11 kV feeder line fault model[cite: 190, 482].*

### **Results & Waveform Analysis**
![Waveform Graph](visuals/rms_analysis.png)
[cite_start]*Figure: Comparative RMS analysis of voltage sags during simulated fault events[cite: 283, 483].*

## 6. Repository Structure
[cite_start]To maintain industrial documentation standards, this repository is organized as follows[cite: 320, 484]:
* [cite_start]**/model**: Contains the `.slx` MATLAB Simulink model file[cite: 429, 484].
* [cite_start]**/publication**: Full-text research paper (PDF) and publication certificate[cite: 450, 485].
* [cite_start]**/visuals**: High-resolution screenshots of the model and comparative results[cite: 458, 486].

---
[cite_start]**License:** This project is released under the **MIT License**[cite: 294, 487].
