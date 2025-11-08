Astrophysics Research Portfolio

This repository consolidates my astrophysics research projects. The work was originally developed under the India Space Academy, and later refined with improved methodology, reproducibility, and presentation. The projects highlight the use of real astronomical datasets, Python-based data analysis, and theoretical modeling in modern cosmology.

Projects

1. Dynamical Mass Estimation of a Galaxy Cluster
	•	Dataset: Sloan Digital Sky Survey (SDSS) spectroscopic observations
	•	Objective: Estimate a galaxy cluster’s dynamical mass from member velocities using the virial theorem
	•	Key Results:
	•	Mean Cluster Redshift (zₘₑₐₙ): 0.08084
	•	Member Galaxies: 91
	•	Velocity Dispersion (σᵥ): 1316 ± 99 km s⁻¹
	•	Dynamical Mass: (6.9 ± 1.4) × 10¹⁴ M☉


2. Supernova Cosmology with Pantheon+SH0ES
	•	Dataset: Pantheon+SH0ES Type Ia Supernovae compilation
	•	Objective: Constrain H₀ and Ωₘ under flat ΛCDM via χ² minimization
	•	Key Results:
	•	H₀ = 72.97 ± 0.26 km s⁻¹ Mpc⁻¹
	•	Ωₘ = 0.351 ± 0.019
	•	Estimated Age of the Universe: ≈ 12.36 Gyr
	•	Context: Results are consistent with late-Universe SH0ES values, but remain in tension with early-Universe CMB-based Planck constraints, illustrating the ongoing Hubble tension.


Tools and Methods

Both projects are implemented in Python, making use of the following ecosystem:
	•	Astropy – cosmology calculations and units handling
	•	SciPy – numerical integration and χ² minimization
	•	NumPy – structured data handling and arrays
	•	Matplotlib – scientific visualization and plotting


This portfolio demonstrates the application of observational data and computational methods to open problems in astrophysics and cosmology.

---

### Note on LaTeX Sources
The LaTeX source files (`.tex`) are included in this repository to ensure full transparency and reproducibility of the research papers. They demonstrate the complete workflow behind the preparation of the final reports, from data analysis in Jupyter notebooks to professional scientific writing. Auxiliary build files (`.aux`, `.log`, `.out`, etc.) are excluded for clarity.

