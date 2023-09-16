# python-finite-volumes

This repository contains cell-centred finite volume codes for:

- Heat conduction
- Stokes (creeping) flow where the pressure gradient is known
- 2D_Solid_Solver _New_Pressure_Gradient06March23.ipynb: An incompressible solid block sagging under its own weight
- Full_NS_channelFlow_central_diff.ipynb: incompressible, laminar channel flow where the convection term is centrally differenced
- Full_NS_channelFlow_upwind_diff.ipynb: incompressible, laminar channel flow where the convection term is upwind differenced
- Stokes_flow_velocity_and_pressure.ipynb:  incompressible, laminar channel flow with no convection term 
- 2D_FSI_wConveciton.ipynb: Laminar channel flow with an incompressible beam attached to the bottom wall of the channel experiencing fluid-structure interaction
- 2D_FSI_wConvection_gravity_benchmark.ipynb: Incompressible beam subject to its own weight and immersed in stationary fluid in a channel. Beam is attached to bottom wall of channel
- FSI_benchmark_Reza2023.ipynb: Test case against a problem in literature. Problem is laminar channel flow with an incompressible beam attached to the bottom wall of the channel experiencing fluid-structure interaction
 - FSI_Convection_add_gradUT.ipynb: Same as 2D_FSI_wConveciton.ipynb but gradU.T term is added explicity to the momentum equations
 
# Author
Eoin Molloy UCD
Uploaded with minor edits by Philip Cardiff UCD
