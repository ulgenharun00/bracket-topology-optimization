# Structural Optimization & Lightweighting of an Industrial Robot Arm Bracket

![SolidWorks](https://img.shields.io/badge/SolidWorks-FF0000?style=for-the-badge&logo=dassaultsystemes&logoColor=white)
![ANSYS](https://img.shields.io/badge/ANSYS-FFB71B?style=for-the-badge&logo=ansys&logoColor=black)

This repository contains the CAD models, FEA simulation results for a topology optimized robot arm bracket under a **500 N peak dynamic load**.

## 📌 Project Overview
* **Objective:** Reduce inertia and mass at the robot flange while strictly preserving structural rigidity and conventional machinability (DFM).
* **Baseline Material:** Structural Steel S235JR
* **Substituted Material:** EN AW-6061-T6 Aluminum Alloy

## 📊 Key Results & Comparison
| Metric / Parameter | Baseline Steel Bracket | Optimized Aluminum Bracket | Change |
| :--- | :---: | :---: | :---: |
| **Mass** | 742.16 g | **199.06 g** | **-73.18%** |
| **Peak von Mises Stress** | 20.67 MPa | 22.64 MPa | Well within yield limit |
| **Static Safety Factor** | 11.37 | **10.60** | Safe |
| **Max Total Deflection** | 0.027 mm | **0.071 mm** | Within L/1000 (0.080 mm) |
| **Fatigue Safety Factor**| 7.02 | **2.65** | Infinite Life (> 10^9 cycles) |

## 🛠️ Software & Standards Used
* **CAD:** SolidWorks (Part Modeling, Technical Drawings)
* **FEA:** ANSYS Mechanical (Adaptive Mesh Convergence, Fatigue Analysis, Topology Optimization)
* **Engineering Standards:** DIN EN 10056-1, ISO 898-1 (Class 8.8 Fasteners), DIN EN ISO 7090, Tabellenbuch Metall

## 📁 Repository Contents
* `/Report`: Complete 26 page engineering report.
* `/CAD`: SolidWorks (.SLDPRT) and neutral (.STEP) exchange models for both designs.
* `/Drawings`: Manufacturing drawings.
* * `/Media` : High resolution stress plots and optimization density maps.
