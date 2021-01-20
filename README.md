# Jupyter Notebooks for solving PDEs
This repository contains the following Jupyter notebooks written in Python, which compute, visualize, and animate solutions to various linear PDEs:

* **Heat Equation 1D:** linear diffusion equation on bounded intervals with Dirichlet and Neumann boundary conditions
* **Laplace Equation 2D:** Laplace equation on the square with inhomogeneous Dirichlet conditions (adapted from code by the Barba group)
* **Transport Equation 1D:** linear advection equation with constant or space-dependent coefficients on bounded intervals with periodic boundary conditions; also plots the characteristic curves
* **Wave Equation 1D and 2D:** linear wave equation on intervals or squares with Dirichlet, Neumann,  or periodic boundary conditions.

If you would like to run these notebooks in your webbrowser using Binder, click on the badge below. It may take time for Binder to start, and the notebooks may also run significantly slower than when ran locally.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sandstede-lab-teaching/Solving_PDEs/main)

Alternatively, install a JupyterLab with a Python 3 kernel locally using, for instance, [Anaconda](https://www.anaconda.com). If the command `%matplotlib widget` results in an error, replace it with `%matplotlib notebook`.
