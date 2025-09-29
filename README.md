# 🌀 NACA Airfoil Flow Simulator

A Python-based airflow visualization tool for **2D NACA airfoils**, demonstrating basic **aerodynamics concepts** such as streamlines, velocity magnitude, and pressure coefficient (Cp).  

This project is a **lightweight CFD-inspired simulation**, showcasing potential flow and airfoil behavior at different **angles of attack**.

---

✨ Features

Generate NACA 4-digit airfoils (e.g., 0012, 2412, 4412)
Automatically computes the upper and lower surface coordinates for standard NACA 4-digit airfoils. This allows the simulation of realistic wing shapes used in aerodynamics studies.

Apply angle-of-attack variations
Rotate the airfoil by a specified angle to simulate different flight or racing conditions. This demonstrates how changing the orientation of the wing affects airflow and lift.

Plot streamlines colored by velocity magnitude
Visualizes airflow patterns around the airfoil using colored streamlines. This makes it easy to see areas of faster or slower airflow and understand how shape and angle affect flow behavior.

Plot pressure coefficient (Cp) to highlight lift and pressure distribution
Calculates a simplified pressure coefficient across the flow field to identify high- and low-pressure regions. This is crucial for understanding lift generation and aerodynamic efficiency.

Compare multiple airfoils side-by-side for easy visual analysis
Automatically generates plots for multiple NACA airfoils in one figure. This allows quick comparison of how different wing shapes and angles impact airflow and pressure.

Fully implemented in Python with numpy and matplotlib
Lightweight and easy to run on any system without requiring heavy CFD software. Ideal for quick simulations, prototyping, or portfolio demonstrations.
---

## 📦 Installation
Clone the repo and install dependencies:

```bash
git clone https://github.com/yourusername/naca-airfoil-sim.git
cd naca-airfoil-sim
pip install numpy matplotlib
