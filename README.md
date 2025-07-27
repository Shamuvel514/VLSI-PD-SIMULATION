# VLSI-PD-SIMULATION
A MATLAB-based simulation of key VLSI Physical Design stages, including standard cell placement, clock tree synthesis (CTS), and static timing analysis (STA) with gate and wire delay modeling. Ideal for EDA and VLSI design enthusiasts.
# VLSI Physical Design Simulation in MATLAB

This project simulates key steps of VLSI Physical Design using MATLAB:
- Standard Cell Placement
- Clock Tree Synthesis (CTS) - simplified
- Static Timing Analysis (STA) with delay modeling

## 🔧 Features
- Randomized standard cell placement
- Custom Netlist (U1–U8) for simulation
- Delay matrix computation using Euclidean distance
- Added gate + wire delay modeling
- Outputs arrival time and worst-case delay

## 📁 Files
- `sta_with_delay.m`: Main simulation script with netlist, placement, and STA
- `Netlist_Struct.m`: (Optional) Netlist as separate MATLAB struct
- `Images/`: (Optional) Screenshots of placement or CTS visualization

## 📷 Sample Output
![Example Placement](Images/cell_placement_example.png)

## 🧠 Concepts Covered
- VLSI floorplanning & physical design
- Clock path analysis
- Delay modeling
- Static timing propagation

## 💡 How to Run
1. Open `sta_with_delay.m` in MATLAB
2. Run the script
3. View plots and timing results in console

---

## ✍ Author
Shamuvel V

💼 B.Tech in VLSI Design & Technology  
🔬 Quantum/VLSI Researcher.
