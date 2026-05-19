# Overview
This repository hosts the compiled literature catalogs, cross-matching routines, and reproducibility scripts for the **Activity and Rotation Catalog (ARC)** presented in Fetherolf, Gupta, Newton et al. (forthcoming); these contents are outlined below. The ARC derives from work undertaken by the Habitable Worlds Observatory Target Stars and Systems working group. Literature catalogs are cross-matched against the Tiers 1-3 HWO target star lists as defined in [Tuchow et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025PASP..137j4402T/abstract). Stellar identifiers and parameter naming conventions are adopted from the HWO Preliminary Input Catalog (HPIC; [Tuchow et al. 2024](https://ui.adsabs.harvard.edu/abs/2024AJ....167..139T/abstract)).

The ARC inlcudes measurements for _v_ sin _i_, _S_-index, _R_'<sub>HK</sub>,  stellar rotation periods, stellar activity cycles, and photometric jitter. The steps to create the final output catalog (`TSS_ARC.csv`) can be reproduced by running the `Cross-matching.ipynb` notebook, which is provided here.

```
└── TSS Activity and Rotation Catalog/              
    ├── catalogs/                # Literature activity catalogs in a consistent format with HPIC naming
    ├── vsini_catalogs/          # As above but for vsini 
    ├── photometry_catalogs/     # As above but for photometry 
    ├── plots/                   # Figures created are (supposed to be) saved here
    ├── HPIC/
    │   ├── HPIC_TSS25.csv       # Tuchow et al. (2025) catalog and tier lists that form the basis for cross-matching
    │   └── HPIC_full_2024.tsv.  # Additional information from Tuchow et al. (2024) not included in the prior
    ├── TSS_ARC.csv              # Resulting table
    ├── Cross-matching.ipynb     # Jupyter nb to perform cross-matching
    ├── Verification.ipynb       # Jupyter nb to verify cross-matching and compare literature catalogs
    └── Plots.ipynb              # Jupyter nb to make plots included in published work
```
