# GEVI Model - Numerical Simulations (v6.2)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18156403.svg)](https://doi.org/10.5281/zenodo.18156403)

This repository contains the computational validations and simulation engine for the **GEVI Model (Emergent Gravity from Informational Saturation of the Vacuum)**.

GEVI is an effective field theory (EFT) that postulates that gravitational attraction emerges from the vacuum's response to the accumulation of information associated with mass-energy, avoiding mathematical singularities through an informational saturation limit.

## 📊 Validated Results in This Version
- **Singularity Removal:** The gravitational potential converges to a finite value $\Phi \to -c^2 I_{crit}$ as $r \to 0$.
- **Newtonian Limit:** The model accurately reproduces classical gravity in weak-field regimes (e.g., solar systems).
- **Shadow Prediction:** A systematic **6.5% reduction** in the shadow radius of compact objects is observed compared to General Relativity.
- **Dynamic Stability:** Validation of the saturated core ("Frozen Core") as a stable attractor for masses in the *mass gap* (2.5–2.8 $M_{\odot}$).

## 📜 Academic Citation
If you use this model, its simulation results, or the source code in your research, please cite the main theoretical framework:

> **Gómez, N. (2025). GEVI: Emergent Gravity from Informational Saturation of the Vacuum (v6.2). Zenodo. https://doi.org/10.5281/zenodo.18156403**

## 💻 Implementation
The main code is located in the file `GEVI Simulations.ipynb` and requires a Python environment with the following dependencies:

```bash
pip install numpy matplotlib
