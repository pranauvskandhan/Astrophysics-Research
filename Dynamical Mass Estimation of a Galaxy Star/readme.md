Dynamical Mass Estimation of a Galaxy Cluster

Overview

This project estimates the dynamical mass of a galaxy cluster using galaxy velocities and the virial theorem. The work was initially developed under the India Space Academy and later refined with updated methodology, cleaner presentation, and extended error analysis.

Dataset
	•	Source: Sloan Digital Sky Survey (SDSS) spectroscopic data
	•	Content: Right Ascension, Declination, spectroscopic redshifts of galaxies in the target cluster field

Methodology
	1.	Data Preprocessing: 3σ clipping to remove outliers from the redshift distribution
	2.	Velocity Dispersion: Derived from member galaxy velocities
	3.	Cluster Radius: Estimated using angular separation and cosmological distances
	4.	Mass Estimation: Virial theorem applied to compute cluster mass

Key Results
	•	Mean Cluster Redshift (zₘₑₐₙ): 0.08084
	•	Cluster Members (after filtering): 91
	•	Velocity Dispersion (σᵥ): 1316 ± 99 km s⁻¹
	•	Cluster Radius (R): (5.70 ± 0.29) × 10⁵ pc
	•	Dynamical Mass (M): (6.9 ± 1.4) × 10¹⁴ M☉

Tools
	•	Python (NumPy, SciPy, Astropy, Matplotlib)
	•	Jupyter Notebook for reproducible analysis