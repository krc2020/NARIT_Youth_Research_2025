**AGN Spectrum Quick Exploration**

This mini-project is designed for a short (15–30 minute) workshop to introduce high‑school students to astronomical spectroscopy. Students will learn how to download a spectrum of an active galactic nucleus (AGN) from the Sloan Digital Sky Survey (SDSS), visualise it, identify common spectral features (continuum, emission and absorption lines) and fit these features with simple models.

**Learning goals**

Fetch spectra from SDSS using the astroquery package.

Convert SDSS FITS spectra into wavelength and flux arrays.

Plot the full spectrum with Matplotlib and zoom in on important features.

Fit the continuum with a low‑order polynomial model.

Fit emission and absorption lines with a Gaussian profile using scipy.optimize.curve_fit.

**Contents**

This repository contains:

"mini_workshop_emission_line_fitting.ipynb" – a Jupyter notebook with step‑by‑step instructions and code for the workshop.

"agn_targets.csv" – a small list of AGN targets (RA, Dec) that students can choose from.

"README.md" – this overview and instructions.

**Quick start (Colab)**

Open the notebook in Google Colab:
https://colab.research.google.com/drive/1-ppty23wb2e_2f_L6HPeGQRrUOUCyQJ3?usp=sharing

Download this workbook and drop it into your Colab account.
Download the data files and put them in your Google Drive folders (recommend naming the folder as "NARIT_Youth_Research_2025/data/").

Install the required packages (if they are not already available):

>> pip install numpy scipy matplotlib astropy astroquery

Run each cell in the notebook in order and follow the prompts and explanations.
If there is "...", you can come up with the solution from the hints and complete the missing code. 

**Requirements**

This workshop assumes basic familiarity with Python and Jupyter notebooks. You will need an internet connection to query SDSS. The notebook uses the following packages:

numpy – numerical arrays and basic math.

matplotlib – plotting spectra.

astropy – FITS handling and astronomical utilities.

astroquery – access to SDSS databases.

scipy – optimisation routines for fitting models.

**Acknowledgments**

Modified from a ThaiPASS2025 workshop: How Giants Grow. Based on public SDSS data and open‑source Python tools.
Ref: Chanchaiworawit & Sarajedini 2024
