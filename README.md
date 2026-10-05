# URECA

NTU URECA project (self-directed), supervised by Prof Liu.

Random Forest prediction of organic fluorophore photophysical properties from molecular structure (SMILES), with Murcko-scaffold train/test splitting to test generalization to new chemical structures.

## Contents

- `URECA_models.ipynb` — single running notebook covering the full pipeline: setup & data loading, EDA, featurization + scaffold split, RF tuning, feature importance, error analysis, write-up.
- `chromophore_data.csv` — chromophore photophysics dataset (20,836 rows), SMILES + solvent + measured absorption max, emission max, extinction coefficient, and quantum yield.

## Targets

- Absorption max (nm)
- Emission max (nm)
- log10(extinction coefficient)
- Quantum yield (Φ_F)
