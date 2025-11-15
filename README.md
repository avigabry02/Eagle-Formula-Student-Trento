# Eagle-Formula-Student-Trento

# UniTrento Eagle Formula SAE Projects: Mechanical and Interface Design

This repository summarizes key design, analysis, and manufacturing projects executed for the UniTrento Eagle Formula SAE team during the 2023-2024 academic year. The work includes optimizing the Anti-Roll Bar (ARB) system mechanics and developing the battery management ground support interface.

---

## Anti-Roll Bar (ARB) System Development

The ARB system required mechanical design, stress analysis, and structural optimization for transition from concept to implementation.

### 1. ARB Pin Dimensioning
The primary goal was to create a **Mathematica program** capable of calculating internal stresses (bending moments and normal forces) on the central support pin. This analysis allowed for dimensioning the pin's diameter and selecting appropriate radial and axial bearings based on the predicted worst-case loading scenario.

### 2. Potentiometer Support
To obtain empirical force values necessary for final dimensioning, custom **supports for potentiometers** were designed in Inventor and 3D-printed. These potentiometers were installed in parallel with the suspensions to measure displacement and derive indicative loads during testing.

### 3. Support Optimization
The main ARB support, which connects the pin and the suspensions, was optimized using **nTopology**. **Topology optimization** was performed to minimize material while maintaining structural integrity. The final design was validated through a static analysis to ensure stresses remained within safe limits (below $200~MPa$) and confirmed with a secondary verification using **Ansys**.

---

## Interface Hand Kart Development

### 4. Interface Hand Kart
This project focused on developing a **modular, easily transportable interface** for the car's battery management cart, replacing a cumbersome system that lacked on-board control. The design, executed in Inventor, included a new sheet metal panel to integrate essential controls and an **LCD screen** for direct battery status monitoring, significantly improving efficiency during tests and races.

---

## Tools Employed

* **Autodesk Inventor:** Used for 3D modeling, designing component supports, and finalizing the ARB assembly and the Hand Kart interface.
* **nTopology:** Utilized for advanced **topology optimization** of the ARB support to achieve maximum efficiency and minimal weight.
* **Mathematica:** Employed for developing the analytical program for ARB pin stress analysis and dimensioning.
* **Ansys:** Used for secondary static analysis verification of the optimized ARB support.

---

## Intended Audience

This repository is a valuable resource for **Formula SAE / Formula Student Teams**, **Mechanical Engineering Students**, and **Design Engineers** interested in:

* Applying **Topology Optimization** to motorsport components.
* Hands-on experience in **CAD design** and manufacturing preparation (3D printing, sheet metal fabrication).
* Integrating analytical stress analysis with practical component dimensioning.
