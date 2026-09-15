# Interferometric Length Measurement

This repository contains numerical simulations and experimental data analysis developed for an interferometric length and thickness measurement project.

The project investigates optical interference, temporal and spatial coherence, fringe visibility, fringe-order ambiguity, and multi-wavelength interferometry for absolute length measurement.

## Project Overview

The project combines theoretical modeling, numerical simulations, and experimental data analysis to investigate the use of optical interferometry for precise dimensional measurements.

The main topics covered include:

- Temporal coherence and wave-packet overlap
- Fringe visibility and coherence length
- Comparison of laser, LED, and white-light coherence
- Multi-wavelength interferometry
- Fringe-order ambiguity and ambiguity resolution
- Spatial filtering using a pinhole
- Michelson interference patterns
- Gaussian beam effects on interference patterns
- Photodiode-based fringe counting
- Experimental wavelength estimation
- Single- and dual-wavelength thickness analysis
- Image-based extraction of fractional fringe information
- Uncertainty analysis

## Repository Contents

### `interferometry_simulations.ipynb`

Contains numerical simulations of the optical phenomena and interferometric measurement methods investigated in the project.

The notebook includes simulations of:

1. Wave-packet recombination and temporal coherence
2. Fringe visibility as a function of optical path difference
3. Coherence-length effects
4. Single-, dual-, and multi-wavelength interferometry
5. Spatial filtering and pinhole performance
6. Michelson interference patterns
7. Gaussian beam effects
8. Photodiode signal and fringe counting

### `experimental_data_analysis.ipynb`

Contains the analysis of experimental interferometry data, including:

- Fringe-counting measurements
- Laser wavelength estimation using linear regression
- Fractional fringe analysis
- Multi-wavelength thickness estimation
- Image-based data extraction
- Repeatability analysis
- Uncertainty estimation

### `interferometer_animations.ipynb`

Contains interactive and animated visualizations of Michelson interferometer behavior.

The notebook includes:

- Light-path animation in a Michelson interferometer
- Double-pass propagation through the compensating plate
- Mirror-angle variation and fringe evolution
- Transition from circular to linear interference fringes
- Dynamic fringe displacement caused by mirror motion
- Comparison of Michelson interferometer configurations with and without a compensating plate

## Methods

The computational analysis was performed using Python and scientific computing libraries including:

- NumPy
- SciPy
- Pandas
- Matplotlib
- OpenPyXL
- RawPy

## Optical System

The simulations and analyses are based primarily on Michelson interferometry and multi-wavelength optical measurement techniques.

The investigated wavelengths include visible laser wavelengths such as:

- 632.8 nm (red)
- 532 nm (green)

## Objectives

The main objective is to investigate numerical and experimental approaches for resolving fringe-order ambiguity and improving the reliability of absolute length and thickness measurements using optical interferometry.

## Status

This repository contains research-oriented simulations and experimental data analysis developed as part of an optical measurement project.
