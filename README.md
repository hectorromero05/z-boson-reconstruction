# Z Boson Reconstruction using ATLAS Open Data

This project aims to reconstruct the Z boson invariant mass peak using open particle-collision data and Python-based analysis tools.

The goal is to develop a reproducible scientific data-analysis workflow inspired by high-energy physics methods used in large-scale experiments such as ATLAS at CERN.

## Objective

The main objective of this project is to identify Z boson candidates through the decay channel:

Z → μ⁺ μ⁻

By selecting events containing two oppositely charged muons and reconstructing their invariant mass, the analysis should produce a mass distribution with a peak close to the known Z boson mass of approximately 91 GeV.

## Physics Background

In high-energy physics experiments, unstable particles such as the Z boson are not observed directly. Instead, they are reconstructed from their decay products.

For the Z → μ⁺ μ⁻ channel, the momenta and energies of two final-state muons can be combined to calculate the invariant mass of the original particle candidate. A peak in the invariant mass distribution near 91 GeV indicates events compatible with Z boson production.

## Methodology

The planned workflow is:

1. Load open particle-collision data.
2. Select events with two muons.
3. Require the muons to have opposite electric charge.
4. Calculate the invariant mass of the dimuon system.
5. Build and visualize the invariant mass histogram.
6. Identify and analyze the Z boson mass peak.
7. Document the results in a reproducible notebook and technical report.

## Tools

This project will use:

- Python
- Jupyter Notebook
- NumPy
- pandas
- Matplotlib
- ROOT / uproot
- Git and GitHub

## Repository Structure

```text
z-boson-reconstruction/
├── data/          # Input data or links to datasets
├── figures/       # Generated plots and visual results
├── notebooks/     # Jupyter notebooks
├── report/        # Technical report
├── src/           # Reusable Python scripts
└── README.md
