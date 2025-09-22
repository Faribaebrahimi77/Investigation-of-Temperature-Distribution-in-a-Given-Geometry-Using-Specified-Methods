# CFD-Analysis-of-Industrial-Melting-Furnace-with-Heat-Transfer-and-Flow-Dynamics
Comprehensive CFD simulation of heat transfer and fluid flow in an industrial melting furnace investigating temperature distribution, flow patterns, and thermal performance optimization.

# Thermal Analysis Objectives
Heat Transfer Investigation

Conduction Analysis: Solid material heat transfer through furnace walls

Convection Effects: Natural/forced convection in furnace interior

Radiation Heat Transfer: High-temperature radiative exchange

Mixed Heat Transfer: Combined conduction-convection-radiation modes

# Flow Dynamics Study

Buoyancy-Driven Flow: Natural convection due to temperature gradients

Recirculation Patterns: Flow circulation zones identification

Velocity Field Analysis: Flow velocity magnitude and direction

Heat Transfer Enhancement: Flow effects on thermal performance

# MATLAB Simulation Methodology
Numerical Methods Implementation

Heat Equation Solver: 2D steady-state heat conduction using finite difference method

Matrix Solution: MATLAB's built-in sparse matrix solvers (mldivide, pcg)

Grid Generation: meshgrid() and linspace() functions for domain discretization

Boundary Conditions: Implemented using MATLAB indexing and matrix manipulation


<img width="602" height="340" alt="image" src="https://github.com/user-attachments/assets/97d32ab8-3016-4bb7-b5ae-64f6f60d7b52" />
<img width="569" height="362" alt="image" src="https://github.com/user-attachments/assets/fa6df043-0a43-467f-9f3d-9ec55e0d804b" />

<img width="705" height="428" alt="image" src="https://github.com/user-attachments/assets/b6c6b3b2-b0e4-4c56-9e4e-758e103af632" />
**

# Results and Conclusion

To summarize the above discussion, it can be noted that for some problems, no analytical solution exists. As mentioned at the beginning of this report, in real-world problems, due to complex geometries and practically countless nodes, analytical solutions are usually impractical. Therefore, one can either proceed with numerical solutions or, in specific cases, resort to experimental approaches.


Numerical solutions, which are the focus of this work, employ various methods and techniques, each of which involves steps to solve complex matrices that essentially contain information about all the nodes.


In this report, two point-wise methods—the Gauss-Seidel and the Jacobi methods—were examined, and the results were analyzed. Various comparisons were made at each step according to the requirements of that section; these detailed comparisons are not presented here. Each section contains the requested analyses and comparisons within itself.
