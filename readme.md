# "Mars – Wanted Dead or Alive" 12,350 BCE: Data Repository
**Institution:** XPS Research Institute  
**P.I. / Author:** B. Vincent Crist (ORCID: 0000-0002-2938-4242)  
**Contact:** bvcrist@xpsresearch.institute  

## 🛰️ Repository Overview
This repository hosts the raw datasets, high-resolution vector figures, and non-equilibrium thermodynamic simulation code supporting the cross-planetary chronological calibration manuscript submitted to *Science* [Crist, 2026]. This open-access index permits peer reviewers and independent researchers to systematically reproduce the astrophysical, kinetic, and paleoclimatological modeling calculations presented in the text.

---

## 📂 Directory Architecture & File Index

### 📁 `01_chronological_data/`
* **`gisp2_raw_signals.csv`**: Calibrated raw data tracks mapping the NOAA/WDS Paleoclimatology GISP2 Central Greenland Temperature Reconstruction anomaly across the common historical axis (16,000 BCE to 8,000 BCE). Tracks the abrupt warming onset at 12,700 BCE and the sudden temperature drop into the freeze valley [Crist, 2026].
* **`cosmogenic_radionuclides.csv`**: Time-series coordinate array of global cosmogenic isotope spikes (¹⁴C, ¹⁰Be, and ³⁶Cl) isolating the acute, 500x high-amplitude flux corresponding to the 12,350 BCE Miyake Extreme Solar Particle Event (ESPE).

### 📁 `02_martian_kinetics/`
* **`interface_enthalpy_calc.py`**: Python execution script validating the energetic threshold overtopping variables required for the flash-volatilization of the ancient northern lowlands (Oceanus Borealis). Governed by the latent heat constant (ΔHvap = 40.7 kJ/mol) [Crist, 2026].
* **`oxychlorine_cascade_matrix.txt`**: Kinetic reaction-rate matrix mapping the 5-step, non-equilibrium gas-phase radical oxidation sequence (Cl -> ClO -> ClO₂ -> ClO₃ -> ClO₄⁻) that precipitated Mars' modern uniform superficial perchlorate blanket.

### 📁 `03_orbital_mechanics/`
* **`parker_spiral_vectors.xlsx`**: Heliospheric coordinate metrics mapping the 120° to 150° wide-angle anisotropic wavefront width along the corotating Interplanetary Magnetic Field (IMF) Parker Spiral streamlines (solar wind velocity Usw ≈ 800 km/s).
* **`ice_cloud_trajectory_sim.out`**: Numerical simulation tracking the inward orbital migration and synodic gravitational capture velocity vectors of the desublimated ice-crystal torus by Earth's gravity well between 12,350 BCE and the terminal arrival benchmark in 12,050 BCE [Crist, 2026].

### 📁 `04_high_res_figures/`
* **`Figure_1_Master_Timeline.pdf`**: Finalized, high-contrast, multi-panel paleoclimate graph featuring the peach-colored Greenland temperature reconstruction curve [Crist, 2026].
* **`Figure_8_Ice_Migration_Schematic.png`**: Top-down heliocentric projection displaying the Solar Minimum Quiet Sun and the 300-year cross-planetary ice transport highway [Crist, 2026].

---

## 🛠️ Execution & Reproducibility Instructions
To verify the interface enthalpy code and run the local boundary ionization parameters locally:
1. Ensure a Python 3.x environment is configured.
2. Execute the master calculation file: `python 02_martian_kinetics/interface_enthalpy_calc.py`
3. The script will output the calibrated metric proving the latent threshold overtopping values (Eflux >> q · mocean) [Crist, 2026].

## 📄 License & Terms of Use