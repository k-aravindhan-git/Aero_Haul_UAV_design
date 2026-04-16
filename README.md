# Aero Haul: Flying-wings Engineering Analysis

[cite_start]This repository contains the engineering analysis, CAD models, and CFD setup for a flying-wing UAV project conducted as part of the Summer Mini Project at the **Aeromodelling Club, Indian Institute of Technology (IIT) Guwahati**. [cite: 1, 3, 4]

## ✈️ Project Overview
[cite_start]Flying wings are a unique class of aircraft characterized by the absence of a distinct fuselage or tail section. [cite: 11] [cite_start]All essential components—payload, fuel, avionics, and propulsion—are integrated within the wing structure itself to minimize drag and enhance aerodynamic efficiency. [cite: 12, 13]

[cite_start]This project explores the aerodynamic characteristics, structural implications, and practical feasibility of flying wings for moderate-speed applications using the **MH60 airfoil**. [cite: 17]

## 🛠 Technical Specifications

### Wing Geometry
[cite_start]The design utilizes a trapezoidal wing configuration with the following parameters: [cite: 189]

| Parameter | Value |
| :--- | :--- |
| **Total Wingspan ($b$)** | [cite_start]$1400\text{ mm}$ ($1.4\text{ m}$) [cite: 180] |
| **Root Chord ($c_r$)** | [cite_start]$250\text{ mm}$ [cite: 182] |
| **Tip Chord ($c_t$)** | [cite_start]$130\text{ mm}$ [cite: 183] |
| **Taper Ratio ($\lambda$)** | [cite_start]$0.52$ [cite: 190] |
| **Mean Aerodynamic Chord (MAC)**| [cite_start]$0.1963\text{ m}$ [cite: 193] |
| **Wing Area ($S$)** | [cite_start]$0.266\text{ m}^2$ [cite: 194] |
| **Wing Sweep ($\Lambda$)** | [cite_start]$20^{\circ}$ [cite: 197] |
| **Aspect Ratio ($AR$)** | [cite_start]$7.368$ [cite: 202] |
| **Winglet Height** | [cite_start]$90\text{ mm}$ [cite: 205] |

### Airfoil Selection: MH60
[cite_start]The **MH60** was selected for its self-stabilizing characteristics, which are critical for tailless aircraft: [cite: 23, 51]
* **Reflexed Camber Line:** Ensures a positive static margin and natural pitch stability. [cite: 53, 171]
* [cite_start]**Low Moment Coefficient ($C_m$):** Helps balance pitching moments without a horizontal stabilizer. [cite: 54]
* **Performance:** Optimized for moderate Reynolds numbers ($100,000$ to $500,000$), making it ideal for UAVs. [cite: 55]

## 📊 CFD Analysis Setup
The aerodynamic performance was validated using **SimScale** with the following parameters: [cite: 238, 239]
* [cite_start]**Velocity Inlet:** $15\text{ m/s}$ (Typical Cruise) [cite: 241]
* [cite_start]**Reynolds Number ($Re$):** $300,000$ [cite: 242]
* **Angle of Attack ($AoA$):** $-5^{\circ}$ to $+15^{\circ}$ [cite: 243]
* [cite_start]**Turbulence Model:** k-omega SST [cite: 244]
* [cite_start]**Mesh:** Fine mesh near the leading edge and control surfaces. [cite: 245]

## 📂 Repository Contents
* `/CAD`: Contains orthographic views and 3D assembly renders. [cite: 234, 235]
* [cite_start]`/Reports`: The full engineering analysis report in PDF format. [cite: 4]
* [cite_start]`/Simulation`: CFD mesh screenshots and volume custom sizing setups. [cite: 256, 266]

## 🔗 External Links
* [cite_start]**3D Model:** [View the complete wing assembly on Autodesk A360](https://a360.co/4etRgx4) [cite: 236]

---
**Author:** Karavindhan [cite: 6]  
**Institution:** Indian Institute of Technology Guwahati [cite: 2]
