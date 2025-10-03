# Galaxy Simulation and Weak Lensing Analysis
## Project Overview
**GalaxyLens** simulates **spiral and elliptical galaxies** using **GalSim**, applies **PSF convolution** and **observational noise**, and demonstrates a small **weak lensing shear**. The main goal is to visualize the effect of PSF, noise, and shear on galaxy images.  

This project provides a **reproducible pipeline** for galaxy simulation and visualization, suitable for learning weak lensing concepts and astrophysical image processing.

---

## Workflow
1. **Simulate Galaxies**
   - Generate spiral and elliptical galaxies with variable flux and half-light radius.
   - Apply PSF convolution and moderate Gaussian/Poisson noise.
   - Apply a small weak lensing shear (g1=0.02, g2=0.01).

2. **Visualize Galaxies**
   - Save simulated galaxies as FITS files in `data/`.
   - Save corresponding PNG images in `plots/`.

---

## How to Run
1. **Clone the repository**
```bash
git clone <your-repo-url>
cd GalaxyLens
```

2.Install requirement
```bash
pip install -r requirements.txt
```
3.Run the simulation and visualization
```bash
python scripts/simulate_galaxies.py
```

Check outputs
-data/ contains FITS images of simulated galaxies.
-plots/ contains PNG visualizations.

GalaxyLens - Simulation Script

This script simulates spiral and elliptical galaxies using GalSim, applies PSF convolution,
adds noise, applies a small weak lensing shear, and saves images.

Results:
- FITS images of galaxies saved in 'data/'.
- PNG visualizations saved in 'plots/'.

Dependencies:
- Python 3.x
- numpy
- matplotlib
- galsim
- astropy

Usage:
1. Run this script to generate simulated galaxy images:
   python scripts/simulate_galaxies.py
2. Check 'data/' for FITS files and 'plots/' for PNG visualizations.
"""


