# Jupyter Notebooks for solving PDEs
This repository contains the following Jupyter notebooks written in Python, which compute, visualize, and animate solutions to various linear PDEs:

* **Heat Equation 1D:** linear diffusion equation on bounded intervals with Dirichlet and Neumann boundary conditions
* **Laplace Equation 2D:** Laplace equation on the square with inhomogeneous Dirichlet conditions (adapted from code by the Barba group)
* **Transport Equation 1D:** linear advection equation with constant or space-dependent coefficients on bounded intervals with periodic boundary conditions; also plots the characteristic curves
* **Wave Equation 1D and 2D:** linear wave equation on intervals or squares with Dirichlet, Neumann,  or periodic boundary conditions.

These notebooks run on a JupyterLab (which can be installed using, for instance, [Anaconda](https://www.anaconda.com)) with a Python 3 kernel. The notebooks require the modules ipywidgets, math, matplotlib, numpy, and scipy. If IPython is used, replace `%matplotlib widget` with `%matplotlib notebook` in each notebook.
