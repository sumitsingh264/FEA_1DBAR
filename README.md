# FEA_1DBAR
This MATLAB project implements a Finite Element Analysis (FEA) approach for solving 1D bar element problems under axial loading. It computes nodal displacements and reaction forces based on user-defined material and geometric properties.

⚙️ Features
Generation of element stiffness matrices.

Assembly of the global stiffness matrix.

Application of boundary conditions and external forces.

Solving the system for unknown displacements.

Calculation of reaction forces at supports.

🧑‍💻 How to Use
Edit Input Parameters
Open the MATLAB script (e.g., bar1d_fea.m) and define:

matlab
Copy
Edit
E = [...]; % Young's modulus for each element
A = [...]; % Cross-sectional area for each element
L = [...]; % Length of each element
forces = [...]; % External force vector
bcs = [...]; % Boundary condition specification
Run the Script

matlab
Copy
Edit
>> bar1d_fea
View Results
The script outputs:

Nodal displacements.

Reaction forces at constrained nodes.

💡 Applications
Axial deformation in truss members.

Introduction to the finite element method (FEM).

Structural mechanics coursework and demonstrations.

📌 Requirements
MATLAB R2018b or later (basic matrix operations; no special toolboxes required).
