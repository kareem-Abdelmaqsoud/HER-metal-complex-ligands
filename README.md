# HER–Metal–Complex–Ligands

This project investigates how ligand identity influences the performance of a nickel metal complex in the Hydrogen Evolution Reaction (HER). The goal is to identify correlations between quantum-chemical descriptors and the experimentally measured hydrogen production.

## Initial Approach

We first examined whether quantum-chemical descriptors correlate with HER activity, beginning with the hydrogen binding energy:

$$
\Delta E\_{\text{bind}} = E(\text{Ni–L–H}) - E(\text{Ni–L}) - \tfrac{1}{2} E(\text{H}\_2)
$$

The binding energy \( \Delta E\_{\text{bind}} \) quantifies the interaction strength between the Ni active site and the ligand \( L \). An optimal binding strength is important:

- **Too strong** binding may block the active site and inhibit catalysis.
- **Too weak** binding may diminish the ligand’s ability to tune the metal center electronically.

# Data-driven Classification Models

Because the mechanism of hydrogen adsorption is not fully understood, we did not observe a strong correlation between the computed adsorption energies and the measured turnover frequencies. Consequently, we shifted to a data-driven approach, using machine-learning models to classify complexes into **high-activity** and **low-activity** categories.
