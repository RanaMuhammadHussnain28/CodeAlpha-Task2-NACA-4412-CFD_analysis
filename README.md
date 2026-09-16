# NACA 4412 Aircraft Wing - CFD Analysis

This repository contains the complete 3D CFD (Computational Fluid Dynamics) simulation setup and results for a **NACA 4412 Aircraft Wing** conducted using **SOLIDWORKS Flow Simulation**.

---

## 🛠️ How to View Simulation Results in SOLIDWORKS

Because SOLIDWORKS Flow Simulation unloads heavy mesh and field data by default to optimize system memory, follow these steps to render the results upon opening:

1. **Clone/Download** this repository ensuring the root folder structure is preserved.
2. Open `Aircraft wing NACA 4412.sldprt` in **SOLIDWORKS**.
3. Go to the **Flow Simulation Analysis Tree** on the left panel.
4. Expand the project tree, scroll down to **Results (Not loaded)**, **Right-Click** it, and select **Load**.
5. All pre-configured **Cut Plots**, **Surface Plots**, and **Flow Trajectories** will automatically load and display on the 3D model.

---

## 📂 Repository Structure

- `Aircraft wing NACA 4412.sldprt` — Main SOLIDWORKS CAD part model.
- `1/` — Mandatory simulation directory containing solver data and binary results (`1.fld`).
- `Reports/` — Complete engineering simulation report in PDF/Word format.
- `Visuals/` — High-resolution renders of pressure distribution and velocity vectors.

---

## 📊 Key Results Summary

- **Solver State**: Fully Converged (>220 iterations)
- **Primary Observations**:
  - Pressure differential captured across the upper (suction) and lower (pressure) surfaces.
  - Clear flow separation and vortex roll-up visualized at the wingtips via Flow Trajectories.
