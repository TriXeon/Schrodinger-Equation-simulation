# Schrodinger-Equation-simulation

This repository implements simulations of the Schrödinger Equation in one, two, and three dimensions using the C programming language. The project aims to provide efficient computational tools for visualizing quantum phenomena.

#Features
1D Schrödinger Equation: Simulate wavefunctions and potentials in one dimension.
2D Schrödinger Equation: Analyze quantum states in two dimensions.
3D Schrödinger Equation: Model complex behaviors in three-dimensional quantum systems.
Flexible initial conditions and boundary handling.
Performance-optimized algorithms for numerical simulations.
Requirements
To build and run this project, ensure you have:

A C compiler (e.g., GCC, Clang)
A Linux or Windows system with a terminal/command prompt
Optional: Libraries for plotting or visualization (e.g., GNUplot)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/Schrodinger-Equation-Simulation.git
cd Schrodinger-Equation-Simulation
Build the source code:

Navigate to the desired simulation folder (1D, 2D, or 3D):
bash
Copy code
cd 1D
Compile the code:
bash
Copy code
gcc -o simulation main_1d.c -lm
Run the simulation:

bash
Copy code
./simulation
Project Structure
bash
Copy code
Schrodinger-Equation-Simulation/
│
├── 1D/
│   ├── main_1d.c        # Source code for 1D simulations
│   ├── potential.c      # Potential definition functions
│   └── README.md        # Documentation for 1D simulation
│
├── 2D/
│   ├── main_2d.c        # Source code for 2D simulations
│   ├── potential.c      # Potential definition functions
│   └── README.md        # Documentation for 2D simulation
│
├── 3D/
│   ├── main_3d.c        # Source code for 3D simulations
│   ├── potential.c      # Potential definition functions
│   └── README.md        # Documentation for 3D simulation
│
├── README.md            # Main project README
└── Makefile             # Optional Makefile for easier builds
Usage
Edit the source files to modify parameters like potential, grid size, or time steps.
Rebuild the project using your compiler.
Visualize results using text-based output or export data for plotting in external tools (e.g., GNUplot, Python).
Contributing
Contributions are welcome! Feel free to:

Submit issues or feature requests.
Fork the repository, make improvements, and open a pull request.
