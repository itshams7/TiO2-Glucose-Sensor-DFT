# TiO2-Based Non-Enzymatic Glucose Sensor Simulation

This repository documents the Density Functional Theory (DFT) analysis of Titanium Dioxide (TiO2) nanostructures for non-enzymatic glucose detection. The study utilizes **Materials Studio (CASTEP)** to model electronic properties and **Adsorption Locator** to evaluate sensor selectivity against interfering agents.

## Project Overview
Current enzymatic glucose sensors suffer from degradation and high manufacturing costs. This project proposes a **Non-Enzymatic TiO2** alternative, optimized via computational modeling to ensure long-term stability and cost reduction.

## Simulation Methodology
*   **Platform:** Materials Studio (CASTEP Module)
*   **Functional:** Generalized Gradient Approximation (GGA-PBE)
*   **Cutoff Energy:** 500 eV
*   **K-Points:** 4x4x4 Monkhorst-Pack (Electronic Properties)
*   **Adsorption Forcefield:** COMPASS

## Key Findings

### 1. Electronic Properties
The geometry optimization resulted in a stable lattice structure with the following parameters:
*   **a = b:** 8.721 Å
*   **c:** 12.394 Å
*   **Band Gap:** 2.41 eV (indicating effective semiconducting behavior for sensing applications).

### 2. Adsorption & Selectivity
The adsorption energy ($E_{ads}$) was calculated using:
$$E_{ads} = E_{total} - (E_{surface} + E_{adsorbate})$$

| Adsorbate | Adsorption Energy (kcal/mol) | Selectivity Status |
| :--- | :--- | :--- |
| **Glucose** | **-31.42** | **Primary Target** |
| Fructose | -28.67 | High Selectivity |
| Urea | -19.53 | Low Interference |

**Conclusion:** Glucose exhibits the strongest binding affinity (-31.42 kcal/mol), confirming that TiO2 can effectively distinguish glucose from common blood interferents like Urea.

## Repository Contents
*   `simulation_config.json`: Exact DFT and Forcefield parameters used in CASTEP.
*   `results_summary.csv`: Raw data table of lattice parameters and energy values.

---
*Author: Shamseldin Abdelrahim*
