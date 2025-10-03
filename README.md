# Galaxy Simulation and Weak Lensing Analysis

# GalaxyLens: Galaxy Simulation and Weak Lensing Analysis

This project demonstrates the simulation of realistic spiral and elliptical galaxies and a quantitative analysis of their shapes under **PSF blurring**, **observational noise**, and **weak gravitational lensing shear** using Python.

---

## Project Overview

The project is divided into **two main parts**:

### Part 1 – Galaxy Simulation and Visualization
- Simulate spiral and elliptical galaxies using **GalSim**.  
- Apply **Point Spread Function (PSF) convolution** and **Gaussian/Poisson noise** to mimic observational conditions.  
- Apply a small **weak lensing shear** to demonstrate its effect.  
- Save simulated galaxy images as **FITS files** and **PNG visualizations**.

### Part 2 – Quantitative Shape Analysis
- Measure galaxy shapes using **adaptive moments**:
  - **Ellipticity (e)**  
  - **Shear components (g1, g2)**  
  - **Moments sigma** (size indicator)  
- Store measurements in a CSV file for reproducibility.  
- Visualize results:
  - **Histogram of ellipticity**  
  - **Scatter plot of g1 vs g2**  
- Analyze and interpret the effects of PSF, noise, and weak lensing shear.

---

## Results

- **Visualizations:**  
  - Galaxies appear realistic with clear spiral and elliptical profiles.  
  - PSF blurring and noise effects are visible in the images.  

- **Shape Measurements:**  
  - Most galaxies have **low to moderate ellipticity**.  
  - Applied weak lensing shear produces **small but measurable shifts** in g1 and g2.  
  - Histograms and scatter plots confirm the quantitative effects of PSF, noise, and shear.

- **Observations:**  
  - PSF slightly rounds galaxies, reducing ellipticity.  
  - Noise introduces small scatter in shape measurements.  
  - Weak lensing shear shifts shapes in a measurable way, validating the pipeline.

---

## Dependencies

- Python 3.x  
- numpy  
- matplotlib  
- pandas  
- seaborn  
- astropy  
- galsim  

Install dependencies via pip if needed:
```bash
pip install numpy matplotlib pandas seaborn astropy galsim
```
## Optional / Additional Work

- Extend the simulation to **larger datasets** for better statistics.  
- Compare **pre- and post-shear measurements** to quantify weak lensing signals.  
- Generate **separate distributions** for spiral vs elliptical galaxies.  
- Explore **correlations between galaxy type and ellipticity/shear**.  

---

## Project Summary

**GalaxyLens** provides a full pipeline from **galaxy simulation** to **quantitative shape analysis**, illustrating how **PSF, noise, and weak lensing shear** affect galaxy observations.  
This project can serve as a foundation for further studies in **astrophysical image analysis** and **weak lensing research**.




