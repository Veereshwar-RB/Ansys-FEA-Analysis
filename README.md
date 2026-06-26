# 🔧 Ansys FEA Analysis Projects

A collection of Finite Element Analysis (FEA) projects built in Ansys Workbench, 
documenting my hands-on practice in structural simulation as part of my 
mechanical engineering coursework and placement preparation.

---

## 📁 Project 1: Static Structural Analysis — L-Shaped Support Bracket

### 🎯 Objective
Evaluate the deformation and strain response of an L-shaped support bracket 
under a small static load, with one end rigidly fixed — a foundational 
exercise in linear static structural FEA.

### 🛠️ Tools & Software
- Ansys Workbench 2026 R1 (Student)
- Modules used: Engineering Data, Geometry, Mesh, Static Structural Solver

### 📐 Model Setup

| Parameter | Detail |
|---|---|
| Geometry | L-shaped bracket — vertical mounting plate (2 bolt holes) joined by a diagonal gusset rib to a horizontal base plate (1 mounting hole) |
| Material | Structural Steel — Density 7850 kg/m³, Tensile Yield Strength 250 MPa, Tensile Ultimate Strength 460 MPa |
| Boundary Condition | Fixed Support — upper hole face of vertical plate |
| Applied Load | 5 N force (ramped), Z-axis direction, on base hole face |
| Mesh | Quad-dominant sheet method, sweep method on solid body |

### 📊 Results

| Result | Maximum | Minimum | Average |
|---|---|---|---|
| Total Deformation (m) | 2.3831e-8 | 0 | 3.8857e-9 |
| Normal Elastic Strain – X axis (m/m) | 2.5438e-8 | -1.5779e-8 | 5.0824e-10 |

### 🎥 Demo Video

Already attach with the name of 626 - Practice (Static Structural)

The video walks through the complete workflow: material assignment → geometry 
review → meshing → boundary conditions → load application → solving → 
result review (deformation and strain).

### 💡 Key Takeaways
- Practiced setting up a complete static structural workflow end-to-end in Ansys Workbench
- Learned to apply and interpret Fixed Support and Force boundary conditions
- Understood how to read Total Deformation and Normal Elastic Strain result plots

---

📌 *More FEA practice projects will be added to this repository as I progress.*
