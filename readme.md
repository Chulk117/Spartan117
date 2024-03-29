Peak Shaving with Microgrid Example.

This work shows how to control voltage rise due to a high PV penetration using a peak shaving strategy for battery energy storage systems. This peak shaving control strategy primary focus involves the charging of the BESS by utilizing the surplus PV production and then discharging of the BESS to the supply the loads when the PV power is lowerthan the load demand during after 1500hr and during the specified peak load demand between 1800hr and 2100hr.

One style of EMS is demonstrated in the "microgrid_WithBESS.slx" model:
- The Peak shaving is approach uses State Machine Logic (Stateflow)

The grid development was inspired by work done from Jonathan Le Sage of Mathworks and the grid was modified with the my input irradiance values, load profile data as well as modifications of the grid infrastructure to best represent POS LV grid. The numerical inputs of the transformers, and the BMS of the BESS was modified by myself.

One can view the original work done by Jonathan Le Sage here:

[![View Microgrid Energy Management System (EMS) using Optimization on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/73139-microgrid-energy-management-system-ems-using-optimization)

## Getting Started


To run this simulation:
1. Extract the files to a directory and navigate to that folder in MATLAB
2. Open the "microgrid_WithBESS.slx" model. This model should automatically add the "Resources" folder to the path
3. Run the model in the Heuristic mode using the slider
4. The MATLAB only folder shows the optimization routine with just MATLAB code (no physical model for verification)

## Toolbox Requirements
- MATLAB
- Optimization Toolbox
- Simulink
- Simscape
- Simscape Electrical
- Stateflow
