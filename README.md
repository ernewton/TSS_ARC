# TSS_ARC
TSS Activity and Rotation Catalog (ARC)

# Overview
This repository hosts the compiled literature catalogs, cross-matching routines, and reproducibility scripts for the catalog presented in Fetherholf, Gupta, Newton et al. (forthcoming). This catalog derives from work undertaken by the Habitable Worlds Observatory Target Stars and Systems working group. Catalogs are cross-matched against the HWO Tiers 1-3 catalog from the HPIC (Tuchow et al.) and include measurements for vsini, S index, R'HK, photometric stellar rotation periods, and photometric jitter.

├── TSS Activity and Rotation Catalog/              
│   ├── catalogs/            # Literature activity catalogs in a consistent format with HPIC naming
│   ├── vsini_catalogs/      # As above but for vsini 
│   ├── photometry_catalogs/ # As above but for photometry 
│   ├── plots/               # Figures created are (supposed to be) saved here
├── HPIC_TSS25.csv           # Tuchow et al. catalog that is the basis for cross-matching
├── HPIC+TSS3.csv            # Resulting table
├── Cross-matching.ipynb     # Jupyter nb to perform cross-matching
├── Verification.ipynb       # Jupyter nb to verify cross-matching and compare literature catalogs
├── Plots.ipynb              # Jupyter nb to make plots included in published work