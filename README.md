# Conformal three-way decisions on concept-lattice classifiers

Code and results for: "Conformal three-way decisions on concept-lattice classifiers
with an exact partial cover, applied to Tamil Nadu seasonal rainfall regimes"
(Uma Maherswari Thathappagaari, Kaspar S; School of Advanced Sciences, VIT, Vellore).

## Contents
- `code/`    notebooks and scripts that produce every table and figure
- `results/` result CSV files used for the tables and figures
- `figures/` final figures (PNG)
- `data/`    NASA POWER seasonal weather data for nine Tamil Nadu locations, 2006-2025

## How to reproduce
1. Install Python 3.10+ with numpy, pandas, scipy, scikit-learn, matplotlib, networkx.
2. Put the NASA POWER data in `data/` (source: https://power.larc.nasa.gov/).
3. Run the pipeline notebook; it writes the files in `results/`.
4. Run the figure cells to rebuild Figures 1-5 from the result files.

All random seeds are fixed. The exact cover is solved with HiGHS through SciPy's `milp`.

## Licence
Code: MIT. Results and figures: CC BY 4.0. NASA POWER data: see NASA's terms.
