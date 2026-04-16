# Aero Haul: Flying-wings Engineering Analysis

This repository contains the engineering analysis, CAD models, and CFD setup for a flying-wing UAV project conducted as part of the **Aero Haul Summer Mini Project** at the **Aeromodelling Club, Indian Institute of Technology (IIT) Guwahati**.

## ✈️ Project Overview
Flying wings are a unique class of aircraft characterized by the absence of a distinct fuselage or tail section[cite: 11]. [cite_start]All essential components—payload, fuel, avionics, and propulsion—are integrated within the wing structure itself to minimize drag and enhance aerodynamic efficiency.

This project explores the aerodynamic characteristics, structural implications, and practical feasibility of flying wings for moderate-speed applications, specifically focusing on the **MH60 airfoil**.

## 🛠 Technical Specifications

### Wing Geometry
The design utilizes a trapezoidal wing configuration with the following calculated parameters:

| Parameter | Value |
| :--- | :--- |
| **Total Wingspan ($b$)** | $1400\text{ mm}$ ($1.4\text{ m}$) |
| **Root Chord ($c_r$)** | $250\text{ mm}$ |
| **Tip Chord ($c_t$)** | $130\text{ mm}$ |
| **Taper Ratio ($\lambda$)** | $0.52$ |
| **Mean Aerodynamic Chord (MAC)**| $0.1963\text{ m}$ |
| **Wing Area ($S$)** | $0.266\text{ m}^2$  |
| **Wing Sweep ($\Lambda$)** | $20^{\circ}$  |
| **Aspect Ratio ($AR$)** | $7.368$  |
| **Winglet Height** | $90\text{ mm}$ |

### Airfoil Selection: MH60
The **MH60** was selected for its self-stabilizing characteristics, which are critical for tailless aircraft:
* **Reflexed Camber Line:** Ensures a positive static margin and natural pitch stability.
* **Low Moment Coefficient ($C_m$):** Helps balance pitching moments naturally.
* **Performance:** Optimized for moderate Reynolds numbers ($100,000$ to $500,000$), making it ideal for UAVs.

## 📊 CFD Analysis Setup
The aerodynamic performance was validated using **SimScale** with the following configuration:
* **Velocity Inlet:** $15\text{ m/s}$ (Typical cruise) 
* **Reynolds Number ($Re$):** $300,000$ 
* **Angle of Attack ($AoA$):** $-5^{\circ}$ to $+15^{\circ}$ 
* **Turbulence Model:** k-omega SST 
* **Mesh Type:** Fine near the leading edge and control surfaces

## 📂 Project Structure
* **Orthographic Views:** Detailed front, side, and top views of the flying wing.
* **3D Assembly:** Complete render of the wing assembly featuring winglets for yaw stability.
* **CFD Visualization:** Pressure distribution ($C_p$), flow separation zones, and vortex visualization near tips.

## 🔗 External Links
* **Interactive 3D Model:** [View the complete wing assembly on Autodesk A360](https://a360.co/4etRgx4)

---
**Author:** K Aravindhan. 
**Institution:** Indian Institute of Technology Guwahati. 
