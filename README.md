# SCSO
Algorithm
# Overview
SCSO (Sand Cat Swarm Optimization) is a population-based metaheuristic optimization algorithm that simulates the hunting behavior of sand cats in nature. The code provided in this repository is mainly applied to dispersion curve inversion for retrieving subsurface layer parameters such as shear wave velocity and layer thickness from geophysical exploration data.
By simulating the search, attack, and prey-catching strategies of sand cats, this algorithm can effectively solve nonlinear, multi-parameter geophysical inverse problems. This code supports Rayleigh wave dispersion curve inversion and is applicable to fields such as engineering geophysics and seismic exploration.

# System Requirements
Hardware Requirements
RAM: Minimum 12 GB (16 GB or more recommended for complex models)

Processor: Any mainstream CPU (Intel Core i5/i7 or equivalent)

Storage: Approximately 10 MB (for storing code and inversion results)

# Software Requirements
Operating System: Windows 10/11, Linux, or macOS (MATLAB-supported versions)

MATLAB Version: R2017a or later

Required Toolboxes:

Statistics and Machine Learning Toolbox (essential)

Optimization Toolbox (recommended, but not required)

#Installation and Setup
1. Download the Code
 `git clone https://github.com/yourusername/SCSO.git`
cd SCSO
2. Add to MATLAB Path
Open MATLAB and run the following command in the command window:
`addpath(genpath('full/path/to/SCSO'));
savepath;  % Optional: save path settings for future sessions`
