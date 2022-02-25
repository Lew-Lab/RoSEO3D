# RoSEO3D
algorithm for jointly estimating the 3D position and 3D orientation of single molecules

This is the main code for RoSEO3D algorithm. For details of this code, please refer to the supplementary 0f pixOL paper.
Wu, Tingting, Jin Lu, and Matthew D. Lew. "pixOL: pixel-wise dipole-spread function engineering for simultaneously measuring the 3D orientation and 3D localization of dipole-like emitters." bioRxiv (2021).

# Analyse_experiment_experiment.m
This code calls RoSEO3D and it prepares data and Microscope parameters for RoSEO3D to analyze.
Two experimental data are included in the folder for your trier.

# Analyse_experiment_beads.m
Different from code ‘Analyse_experiment_experiment.m’, this code analyses beads that locate at the coverslip, but the objective is scanning the beads. So this code estimates the normal focal plane of the objective, lateral position and 3D orientation of beads.

# Analyse_MonteCarlo.m
Monte Carlo simulation of designed phase mask using RoSEO3D

# Nanoscope.m
Prepare the microscope

