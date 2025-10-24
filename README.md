# SunSolve P90 Uncertainty Analysis

This repository contains Python functions and tools for analyzing uncertainty in photovoltaic (PV) yield forecasts using [SunSolve](https://sunsolve.com)'s P90 client. The P90 client enables users to simulate uncertainty in their solar energy predictions, providing valuable insights for risk assessment and project planning.

## Overview

The P90 client helps solar energy analysts and engineers:
- Simulate uncertainty in PV yield forecasts
- Apply Gaussian, Weibull and Skewed Gaussian error functions to a variety of variables
- Apply errors on a global (simulation) level, yearly level and time-step level, independently
- Generate P90 estimates for conservative planning, along with any other P-values (percentile values)
- Visualize yield histograms relative to the P50 yield of each year (does not estimate absolute yields)

## Repository Contents

- `P90 Analysis.ipynb` - Core Jupyter notebook containing the workflow to run uncertainty analysis on your system
- `UncertaintyFunctions.ipynb` - Helper Jupyter notebook containing Python functions for uncertainty analysis
- `Jupyter Notebook Intro.ipynb` - "Intro to Jupyter notebooks" tutorial for beginners
- `sunsolve_p90_client-0.1.0.170+dev-py3-none-any.whl` - P90 client Python package
- `Data/` - Folder containing sample data files (e.g., `sydney.pvw`)
- `Images/` - Folder containing images for branding and tutorial

## Requirements

All users must first [signup for access](https://www.sunsolve.com/p90/signup/). In addition, you will need:

* [Google Colab](https://colab.research.google.com/github/pvlighthouse/SunSolveP90/blob/main/P90%20Analysis.ipynb); **OR** the below:
* Python 3+ (https://www.python.org/downloads/)
* pip 20+ (https://pypi.org/project/pip/ )
* Jupyter (run `pip install jupyter` from terminal)
* numpy, scipy, matplotlib, plotly, pandas (run `pip install numpy pandas plotly scipy matplotlib openpyxl` from terminal)
* git (for cloning the repository, alternatively you may just [download it](https://github.com/pvlighthouse/SunSolveP90/archive/refs/heads/main.zip) manually)

## Getting Started

Follow the steps in [docs.sunsolve.com/en/p90/getting-started/](http://docs.sunsolve.com/en/p90/getting-started/).

## About SunSolve

[SunSolve](https://sunsolve.com) provides advanced solar energy simulation and analysis tools. The P90 client is part of SunSolve's suite of professional solar analytics solutions.