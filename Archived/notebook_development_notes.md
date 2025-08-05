# Legacy Notebook Development (Waveframe_Fits.ipynb)

This folder contains early-stage attempts at interactive validation using Jupyter/Colab notebooks. While useful for exploratory work, this approach was deprecated due to the following limitations:

- Inconsistent execution across devices (especially mobile)
- Import and runtime issues in Colab
- Difficult workflow for version control and collaboration
- Poor reproducibility compared to standalone scripts

---

## What Was Attempted

The notebook `Waveframe_Fits.ipynb` included:

- Residual plots for:
  - \( H(z) \) vs. Pantheon/BAO
  - \( \mu(z) \) vs. Supernova (Pantheon+)
  - \( f\sigma_8(z) \) vs. RSD
- Fit statistics: \( \chi^2 \), AIC, BIC
- Model integration using the Waveframe v3.1 expansion law

---

## Why It Was Archived

The notebook workflow proved to be more trouble than it was worth. Instead, validation is now handled via modular Python scripts using:

- Clean imports
- Reproducible command-line execution
- No GUI or runtime dependencies

See `/validation/` folder for the maintained analysis tools.

---

## Note

If revisiting Jupyter/Colab becomes necessary (e.g. for educational or outreach purposes), this archived version serves as a baseline. No further development is planned here.
