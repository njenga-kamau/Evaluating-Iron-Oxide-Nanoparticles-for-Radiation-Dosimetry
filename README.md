# Evaluating-Iron-Oxide-Nanoparticles-for-Radiation-Dosimetry

This repository contains the analysis and code used for the study titled "Evaluating the Utility of Iron Oxide Nanoparticles for Pre-Clinical Radiation Dose Estimation". The study investigates the potential use of ferumoxytol nanoparticles for radiation dosimetry, leveraging their oxidation properties under ionizing radiation. This repository outlines the steps taken to analyze the data, including chemical preparation, electron paramagnetic resonance (EPR) spectroscopy, and dose estimation.

Table of Contents:
1. Introduction
2. Project Structure
3. Analysis Workflow
4. Key Findings
5. Acknowledgments
   
Introduction:
The study explores the feasibility of using superparamagnetic iron oxide nanoparticles (SPIONs) as modern alternatives to traditional Fricke dosimeters for radiation dosimetry. By oxidizing the Fe2+ sites of ferumoxytol nanoparticles (Fe3O4), it is possible to measure radiation dose delivery using EPR spectroscopy. The research aimed to test the linearity, sensitivity, and reliability of ferumoxytol oxidation under varying radiation conditions.

Project Structure:
The repository includes the following directories:

Chemical Preparation: Code for diluting ferumoxytol and preparing xylenol orange solutions for experiments.
Data Collection: Scripts for conducting EPR spectroscopy and collecting spectroscopic data.
Data Analysis: Python scripts for analyzing EPR signal intensity, dose estimation, and evaluating linearity.
Visualization: Jupyter notebooks for generating plots and figures, including EPR spectra and dose-response curves.

Analysis Workflow
Chemical Preparation:

Ferumoxytol was diluted to specific concentrations in water or xylenol orange.
Samples were irradiated with a cesium-137 source at a dose rate of 0.6 Gy/min.
Data Collection:

EPR spectroscopy was used to measure changes in nanoparticle oxidation post-irradiation.
Signal intensity at g ≈ 2 was recorded for different ferumoxytol concentrations and doses.
Data Analysis:

Dose-response curves were generated to evaluate the linearity of ferumoxytol oxidation up to 20 Gy.
Statistical analyses were performed to compare predicted doses with actual delivered doses.
Visualization:

Plots showcasing EPR signal intensity changes, dose prediction errors, and linearity across doses were created.

Key Findings:
EPR spectroscopy successfully detected ferumoxytol oxidation post-radiation.
Linearity of ferumoxytol oxidation was observed up to 10 Gy for 150 nM concentrations and 20 Gy for 500 nM concentrations.
Xylenol orange was not sensitive enough to detect nanoparticle oxidation due to low Fe3+ release.
Radiation dose predictions with ferumoxytol underestimated the actual dose by 79.2%, indicating a high sensitivity to dose rates.

Acknowledgments:
This study was supported by NIH grant R21CA270742 and the Radiation Research Foundation. Core facilities were supported in part by the Carver College of Medicine and the Holden Comprehensive Cancer Center.

