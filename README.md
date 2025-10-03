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
Install dependencies

bash
Copy code
pip install -r requirements.txt
Run the simulation and visualization

bash
Copy code
python scripts/simulate_galaxies.py
Check outputs

data/ contains FITS images of simulated galaxies.

plots/ contains PNG visualizations.



