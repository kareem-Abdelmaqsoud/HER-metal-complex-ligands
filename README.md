# HER-metal-complex-ligands

This project focuses on understanding the effect of ligand choice on the performance of a Nickel metal complex in the Hydrogen Evolution Reaction (HER). This goal to find a correlation between quantum chemistry descriptors and the concentration of hydrogen produced.

## Initial Approach

Use these to descriptors and check whether they correlate with the experimental results.

$$
\Delta E_{\text{bind}} = E(\text{Ni–L}) - E(\text{Ni}) - E(\text{L})
$$

The binding energy ($\Delta E_{\text{bind}}$) describes the strength of interaction between the Ni active site and the ligand $L$. A moderate binding strength is essential: too strong binding can block active sites, while too weak binding can reduce the electronic tuning effect of the ligand.

---

$$
\Delta G_{H} = G(\text{Ni–L–H}) - G(\text{Ni–L}) - \tfrac{1}{2} G(\text{H}_{2})
$$

The free energy of hydrogen adsorption ($\Delta G_{H}$) is a widely used descriptor for HER performance. An optimal catalyst should have $\Delta G_{H} \approx 0$ so that protons/electrons can adsorb and desorb efficiently. Deviations from zero (either positive or negative) lead to slower reaction kinetics.

---

Since the ligand binding energy ($\Delta E_{\text{bind}}$) modifies the electronic structure of Ni sites, it directly affects hydrogen adsorption thermodynamics ($\Delta G_{H}$). Therefore, $\Delta E_{\text{bind}}$ and $\Delta G_{H}$ are expected to correlate, together governing the catalytic efficiency for the hydrogen evolution reaction (HER).
