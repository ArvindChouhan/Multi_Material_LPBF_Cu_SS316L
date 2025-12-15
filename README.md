# Multi_Material_LPBF_Cu_SS316L
The shared OpenFOAM code simulates the mixing of two materials using Laser Ray Tracing in the LPBF process. In this particular code, a case study of the Cu–SS316L system is presented.

# Software:
OpenFoam v2006

# Attachemnts:
 1. Case file 2. Solver

# 🛠️ Custom OpenFOAM Solver: [MMCS]
This repository contains the source code for MMCS, a custom solver developed using the OpenFOAM C++ library. This solver is based on the intermixingFoam framework and is designed to simulate mixing of two materials using Laser Ray Tracing in the LPBF process.

# 🚀 Getting Started
Prerequisites

To compile and run this solver, you must have a working installation of OpenFOAM v2006.
Set up the environment: Ensure your OpenFOAM environment is sourced (e.g., source $HOME/OpenFOAM/OpenFOAM-v2006/etc/bashrc).

Compile the solver from directory: .\MMCS\MMCS

    wmake

    Upon successful compilation, the executable [Solver Name] will be located in your $FOAM_USER_APPBIN directory.

📁 Directory Structure
Folder/File	Description
MMCS.C	Main C++ source file containing the solver loop and equation setup.
Make/files	Specifies the source files to compile.
Make/options	Specifies the necessary libraries and include paths.
Raytracing directory is included.
Case file is available for testing the solver.

# ⚙️ How to Run a Tutorial Case

In case directory:
Run the standard OpenFOAM setup utilities (if necessary):
Bash

blockMesh
setFields

Execute the custom solver:
MMCS

View the results using ParaView:
paraFoam
