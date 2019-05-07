# Magnitude Intensity Correction

Click on the Jupyter Notebook [Intensity Correction.ipynb](https://github.com/korbinian90/Magnitude-Intensity-Correction/blob/master/Intensity%20Correction.ipynb) for a demonstration. (you need to request the desktop version if you are on mobile)

The source code is found in [MRI.jl](https://github.com/korbinian90/MRI.jl) together with installation instructions.

This work will be presented as an ePoster at the ISMRM 2019: #2716 "A Simple Homogeneity Correction for Neuroimaging at 7T"

## Abstract

A wide range of MR sequences produce inhomogeneous magnitude images due to the coil sensitivities varying inside the volume, which is especially severe for ultra-high field strengths. The optimum solution would be a homogeneous reference coil, which however is not possible at a field strength of 7T due to the shorter wavelength. To date, correction methods require very long computation times rendering them impractical for on-console imaging. We propose a new magnitude inhomogeneity correction approach, which is based on simplified segmentation and fast interpolation to estimate the bias field. The resulting images show high homogeneity across all three dimensions without any visible artifacts.
