# Computational Study of TiO₂-Based Glucose Sensing

**Undergraduate research | Density functional theory | Materials simulation**

## Overview

A computational investigation of titanium dioxide (TiO₂) structures for non-enzymatic glucose-sensing applications. The project examines electronic properties and the relative adsorption behaviour of glucose and selected interfering molecules.

## Methods

- **Simulation platform:** BIOVIA Materials Studio
- **Electronic-structure calculations:** CASTEP, using GGA-PBE
- **Adsorption analysis:** Adsorption Locator / COMPASS force field
- **Comparison molecules:** Glucose, fructose and urea

Configuration details are documented in `simulation_config.json`.

## Reported Results

The repository's summary dataset records the following values:

| Parameter | Reported value |
| --- | ---: |
| Band gap | 2.41 eV |
| Glucose adsorption energy | −31.42 kcal/mol |
| Fructose adsorption energy | −28.67 kcal/mol |
| Urea adsorption energy | −19.53 kcal/mol |

These values are presented as the results recorded in this repository. The summary files alone do not establish experimental sensor performance.

## Repository Contents

- `simulation_config.json` — Documented modelling settings
- `results_summary.csv` — Tabulated reported simulation outputs
- `README.md` — Research overview

## Scope and Limitations

This repository is a compact research summary rather than a complete archive of raw Materials Studio project files or a fully reproducible calculation workflow. Findings concern computational modelling, not laboratory-validated device performance.

## Author

Shamseldin Abdelrahim
