
# PN Junction Diode I-V Curve Simulator

This project is a Python-based simulation that models the current-voltage (I-V) characteristic of a semiconductor PN junction diode.

## Description

The simulation implements the Shockley Diode Equation to generate the diode's I-V curve. It also includes an analysis of how the device characteristics change with varying temperatures.

### Physics Background

The core of the simulation is the Shockley Diode Equation:
`I = Is * (exp(Vd / (n * Vt)) - 1)`

## Technologies Used
- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Results

### Single Diode I-V Curve at 27°C
<img width="736" height="564" alt="Screenshot 2025-07-28 154908" src="https://github.com/user-attachments/assets/74886db7-9d37-4594-b1bb-56dc5d9f5c8c" />


### I-V Curve Dependence on Temperature
<img width="783" height="568" alt="Screenshot 2025-07-28 155140" src="https://github.com/user-attachments/assets/842ff793-582a-4b25-b413-81c1e91191ea" />
