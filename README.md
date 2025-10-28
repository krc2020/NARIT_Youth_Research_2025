AGN Spectrum Quick Exploration
This mini-project is designed for a short (15–30 minute) workshop to introduce high‑school students to astronomical spectroscopy. Students will learn how to download a spectrum of an active galactic nucleus (AGN) from the Sloan Digital Sky Survey (SDSS), visualise it, identify common spectral features (continuum, emission and absorption lines) and fit these features with simple models.
Learning goals
•	Fetch spectra from SDSS using the astroquery package.
•	Convert SDSS FITS spectra into wavelength and flux arrays.
•	Plot the full spectrum with Matplotlib and zoom in on important features.
•	Fit the continuum with a low‑order polynomial model.
•	Fit emission and absorption lines with a Gaussian profile using scipy.optimize.curve_fit.
Contents
This repository contains:
•	mini_workshop.ipynb – a Jupyter notebook with step‑by‑step instructions and code for the workshop.
•	data/agn_targets.csv – a small list of AGN targets (RA, Dec) that students can choose from.
•	README.md – this overview and instructions.
Quick start (Colab)
1.	Open the notebook in Google Colab:
https://colab.research.google.com/github/<your‑username>/<this‑repo>/blob/main/mini_workshop.ipynb
Replace <your‑username> and <this‑repo> with your GitHub user name and repository name after you fork this project.
2.	Install the required packages (if they are not already available):
pip install numpy scipy matplotlib astropy astroquery
1.	Run each cell in the notebook in order and follow the prompts and explanations.
Requirements
This workshop assumes basic familiarity with Python and Jupyter notebooks. You will need an internet connection to query SDSS. The notebook uses the following packages:
•	numpy – numerical arrays and basic math.
•	matplotlib – plotting spectra.
•	astropy – FITS handling and astronomical utilities.
•	astroquery – access to SDSS databases.
•	scipy – optimisation routines for fitting models.
Acknowledgments
Developed for a ThaiPASS 2025 outreach workshop. Based on public SDSS data and open‑source Python tools.
 
