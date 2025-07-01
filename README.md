# Estimating the age of the universe from Type Ia Supernovae

This project presents a computational analysis for estimating the age of the universe using Type Ia supernovae observational data. The notebook implements numerical integration, cosmological model fitting, and residual analysis to determine the Hubble constant (H₀), the matter density parameter (Ωₘ), and the corresponding age of the universe under the ΛCDM model. 

---

## Features

- Parses and analyzes Type Ia supernovae data (Pantheon+SH0ES)
- Fits cosmological parameters (H₀ and Ωₘ) using non-linear least squares
- Estimates the age of the universe via numerical integration of the cosmological model
- Plots the Hubble diagram (distance modulus vs redshift) and residuals
- Compares parameter fits across different redshift ranges
- Modular Python functions for reproducibility

---


---

## Data

⚠ **Note:**  
This project uses the Pantheon+SH0ES Type Ia supernovae dataset.  
➡ The dataset is **not included** in this repository.  
➡ Please download it separately from the official source:  
You can find the dataset [here](https://github.com/PantheonPlusSH0ES/DataRelease/blob/main/Pantheon%2B_Data/4_DISTANCES_AND_COVAR/Pantheon%2BSH0ES.dat).


Update the notebook file path accordingly after downloading.

---

## Requirements

- Python 3.x  
- numpy  
- pandas  
- matplotlib  
- scipy  
- astropy  

You can install these using:
```bash
pip install numpy pandas matplotlib scipy astropy
```

---

## How to Run

1️⃣ Download the Pantheon+SH0ES dataset from the official source and place it in your working directory.  

2️⃣ Open and run the notebook:

3️⃣ The notebook will perform model fitting, plot results, and estimate the universe’s age.

---

## Future Work

Planned extensions include:
- Exploring alternative cosmological models (spherical and hyperboloidal)
- Comparing LCDM with wCDM
- Adding interactive visualizations

---


