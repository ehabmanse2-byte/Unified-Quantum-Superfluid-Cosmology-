# Unified Quantum Superfluid Cosmology: Numerical Simulations & MCMC Parameter Estimation

[![ORCID](https://shields.io)](https://orcid.org)
[![DOI](https://zenodo.org)](https://doi.org)
[![License: MIT](https://shields.io)](https://opensource.org)
[![Open In Colab](https://google.com)](https://google.com)

Official computational repository accompanying the theoretical physics manuscript:
> **"Space-time as a Unified Quantum Fluid Model for Dark Components, Quantum Phenomena, and Ordinary Matter: Theoretical Framework, Mathematical Appendix, and Empirical Benchmarks"**  
> *Author:* Ehab Mohamed Abdel Gwad Manse (Independent Researcher, Cairo, Egypt)  
> *ORCID:* [0009-0009-4846-6188](https://orcid.org)
> *DOI:* [10.5281/zenodo.24355406]
---

## Overview

This repository provides six fully reproducible Python / Jupyter Notebook simulations validating the analytical formulations of the **Unified Dark Fluid** model. Replacing the classical assumption of an unbounded cosmos with a finite, topologically closed zero-viscosity quantum superfluid sustained by an external high-frequency boundary oscillation, these scripts reproduce the 3D hydrodynamic surfaces, multi-messenger dispersion bounds, and Bayesian MCMC parameter constraints presented in **Appendix C (Figures 1–6 & Table 3)** of the manuscript.

---

## Interactive Google Colab Notebooks

Click any badge below to launch and execute the corresponding simulation directly in your browser via Google Colab without local installation:

| Simulation ID | Notebook Title | Manuscript Reference | Interactive Launch |
| :--- | :--- | :--- | :--- |
| **Sim 1** | `Sim1_3D_Hubble_Expansion.ipynb` | Section C.1, Eq. (12), **Figure 1** | [![Open In Colab](https://google.com)](https://google.comdrive/1Jl2KwySGR8Jh97-HpmOZcE5Drhh43e3B) |
| **Sim 2** | `Sim2_3D_GW_Neutrino_Dispersion.ipynb` | Section C.2, Eqs. (9)–(10), **Figure 2** | [![Open In Colab](https://google.com)](https://google.comdrive/1W14P-d_mjqrn_R-wR99lcH_UnVM07Jvx) |
| **Sim 3** | `Sim3_3D_Macro_Quantum_Loop.ipynb` | Section C.3, Eq. (6), **Figure 3** | [![Open In Colab](https://google.com)](https://google.comdrive/1S2kHtIezt92HTV7Y4FF9JFE3-wkQnfNB) |
| **Sim 4** | `Sim4_MCMC_Parameter_Estimation.ipynb` | Section C.4, **Figure 4 & Table 3** | [![Open In Colab](https://google.com)](https://google.comdrive/1OBCw5mSGpvNv9jvvXskuQzNeQlqAuZSO) |
| **Sim 5** | `Sim5_3D_CERN_Higgs_Fluctuations.ipynb` | Section C.5, Eq. (7), **Figure 5** | [![Open In Colab](https://google.com)](https://google.comdrive/1vTyjKIvdV4G3_LOPz_9TdbeRQ4HGcYQX) |
| **Sim 6** | `Sim6_3D_EHT_Horizon_Shear.ipynb` | Section C.6, Eq. (8), **Figure 6** | [![Open In Colab](https://google.com)](https://google.comdrive/1r39rMeT21eadCxXkfTKHodEZYwIsFb4G) |

---

## Description of Simulations

### 1. `Sim1_3D_Hubble_Expansion`
* **Physics Modeled:** 3D Cosmic Expansion History $H(z, \rho_{\mathrm{DE}}/\rho_{\mathrm{DM}})$ and dynamic Dark Energy equation of state $(w_0, w_a)$.
* **Key Result:** Demonstrates how local acoustic resonance amplification in cosmic voids ($\rho_{\mathrm{DE}} > \rho_{\mathrm{DM}}$) elevates the local Hubble rate $H_0$, resolving the Hubble tension and reproducing DESI DR1 evolving Dark Energy parameters ($w_0 \approx -0.82, w_a \approx -0.75$).

### 2. `Sim2_3D_GW_Neutrino_Dispersion`
* **Physics Modeled:** Coupled 3D multi-messenger dispersion surfaces for high-frequency gravitational waves (LIGO/NANOGrav) and high-energy astrophysical neutrinos traversing void phase gradients $\nabla S$ (IceCube).
* **Key Result:** Constrains the acoustic cutoff frequency to $\nu_0 \lesssim 7.7\,\mathrm{nHz}$ (consistent with GW150914 arrival bounds $\Delta t < 2\,\mathrm{ms}$) and matches cumulative neutrino flavor-ratio shifts ($|\Delta P| \approx 0.037$) across gigaparsec voids.

### 3. `Sim3_3D_Macro_Quantum_Loop`
* **Physics Modeled:** Spatiotemporal evolution of normalized substrate density $\rho/\rho_{\mathrm{crit}}$ governed by the modified continuity equation across *The Barzakh* (Critical Quantum Phase Interface).
* **Key Result:** Validates closed-loop mass-energy conservation between stellar nucleosynthesis sinks ($\Gamma_{\mathrm{stars}}$) and Black Hole event-horizon phase-shear recycling sources ($\Gamma_{\mathrm{BH}}$) without singularities.

### 4. `Sim4_MCMC_Parameter_Estimation`
* **Physics Modeled:** Metropolis–Hastings Markov Chain Monte Carlo (MCMC) Bayesian parameter estimation ($50,000$ steps, $10,000$ burn-in) jointly fitted to DESI DR1/SDSS BAO scale shifts, Planck 2018 CMB hemispherical dipole asymmetry ($A_{\mathrm{res}} \approx 0.072$), and the dark-sector equilibrium ratio.
* **Key Result:** Recovers marginalized 68% confidence limits: $\beta = 0.120 \pm 0.038$, $\epsilon_{\mathrm{dip}} = 1.180 \pm 0.350$, and $\mathcal{R}_{\mathrm{crit}} = 0.460 \pm 0.015$.

### 5. `Sim5_3D_CERN_Higgs_Fluctuations`
* **Physics Modeled:** 3D invariant Higgs boson mass fluctuation surface $\Delta m_H(\chi, \gamma)$ near the critical phase boundary contrasted against the combined ATLAS LHC experimental precision floor ($\pm 0.11\,\mathrm{GeV}$).
* **Key Result:** Confirms that standard collider vacuum conditions remain safely offset from the phase boundary ($\Delta m_H \approx 0.058\,\mathrm{GeV}$ at $\chi \gtrsim 1.4$), while predicting a distinct $\sim 1.3\,\mathrm{GeV}$ resonance spike near criticality.

### 6. `Sim6_3D_EHT_Horizon_Shear`
* **Physics Modeled:** 3D event-horizon Phase Shear Zone boundary thickness $\Delta R_{\mathrm{horizon}}(\lambda_{\mathrm{superfluid}}, \xi)$ mapped against Event Horizon Telescope (EHT) M87* shadow-sharpness bounds ($\lesssim 12.8\,\mathrm{AU}$) and future space-based VLBI thresholds ($1.0\,\mathrm{AU}$).
* **Key Result:** Replaces classical point singularities with a finite superfluid healing-length boundary layer where gravitational phase shear collapses the Higgs barrier.

---

## Local Installation & Usage

To run the notebooks locally, clone the repository and install the dependencies (`numpy`, `scipy`, `matplotlib`, `jupyter`) via pip.

---

## Citation

Please cite the simulation codes or theoretical formulations using the provided BibTeX entry for Ehab Mohamed Abdel Gwad Manse's work.

---

## Contact

* **Author:** Ehab Mohamed Abdel Gwad Manse
* **Email:** ehabmanse2@gmail.com
* **ORCID:** https://orcid.org
(https://orcid.org/0009-0009-4846-6188))
