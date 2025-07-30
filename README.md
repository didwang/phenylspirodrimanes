# phenylspirodrimanes

This repository contains code and data for generating and analyzing a virtual library of phenylspirodrimanes. The goal is to explore chemical diversity by enumerating natural product-inspired drimane/spirodrimane cores with commercially available ortho-halophenols, followed by cheminformatics-based property calculations and chemical space visualization.

Contents

📒 Notebooks
Chemical Space of enumerated compounds.ipynb
Interactive notebook for property calculation, dimensionality reduction (e.g., t-SNE), and visualization of the chemical space.

Enumerated products from Enamine database.ipynb
Notebook for generating enumerated phenylspirodrimane derivatives from drimane/spirodrimane cores and ortho-halophenols.

📂 Data Files

Drimanes.csv
List of drimane scaffolds used as core structures.

Spirodrimane_monomer.csv
Collection of natural spirodrimane monomers.

Enamine_Orthohalophenol.csv
Commercially available ortho-halophenols sourced from Enamine.

final_products_Enamine.csv
Final filtered set of enumerated phenylspirodrimane products from Enamine sources.

all_product_info.csv
Master dataset of natural and enumerated compounds with computed properties, SMILES, and metadata.

Environment
All analyses were performed in Python 3.9.7 on macOS (x86_64) using the following packages:

RDKit 2021.09.2

Scikit-learn 1.2.1

Pandas 1.3.4

NumPy 1.26.4

Matplotlib 3.9.2

Seaborn 0.13.2

Plotly 5.5.0

Dash 2.0.0
