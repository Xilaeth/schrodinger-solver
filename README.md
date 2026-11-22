# Numerical Solver for the Schrodinger Equation

This projects implements a Crank-Nicolson and Gauss-Seidel based numerical solver for the one- and two-dimensional Schrodinger Equation.

The project was written within a two-week time span as part of a high school internship in Prof. Dr. Roser Valenti's research group at
the University of Frankfurt.

A short write-up from 2023 can be found in the `Numerical solution of the Schrödinger equation.pdf` file.

> **Status:** Archived personal project - cleaned up for reference

## Features
- Includes C++ code for numerically solving the two dimensional Schrodinger Equation
- Includes Python code for visualizing the system dynamics

## Prerequisites

Originally written 3+ years ago without strict pinned version numbers. 

- **Python:** 3.8+ 
- **C++:** C++14 or C++17 compatible compiler (e.g. `g++` or `clang`)
- **FFMPEG:** Required for video handling (exact version not pinned but any modern version should generally work)
- **Libraries:**
    - **Eigen** (C++ linear algebra header library)
    - **matplotlib** (Python plotting)
    - **vispy** (Python interactive visualization)

## Getting Started

The code for the different implementation steps of the projects can be found in the `code/` folders.

To run the simulation you can either use the shell-script `run.sh` or compile the C++ code using Eigen manually and visualize it using one
of the Python files. Finally, the visualization can be turned into an `.mp4` file using the `make-vid.sh` shell-script that uses FFMPEG.

Licensed unter the MIT License.
