This repository contains data and code supporting the informatics-driven synthesis and chemical space analysis of phenylspirodrimanes and related analogs.

📁 Contents

📒 Notebooks

spiro_library/

Enumerated products from Enamine database.ipynb
Notebook for generating enumerated phenylspirodrimane derivatives from drimane/spirodrimane cores and ortho-halophenols.

Chemical Space of enumerated compounds.ipynb
Interactive notebook for property calculation, dimensionality reduction (e.g., t-SNE), and visualization of the chemical space.

hydrazone cross coupling/

Visualization_each category.ipynb
Jupyter notebook for analyzing and visualizing reaction categories in hydrazone-based cross-coupling reactions curated from Reaxys.

📊 Data Files

spiro_library/

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

hydrazone cross coupling/

final_cleaned_Reaxys_data.xlsx
Cleaned dataset of hydrazone cross-coupling reactions from Reaxys, filtered and grouped by substrate category.

💻 Environment
All analyses were performed in Python 3.9.7 on macOS (x86_64) using the following packages:

RDKit: 2021.09.2

scikit-learn: 1.2.1

pandas: 1.3.4

numpy: 1.26.4

matplotlib: 3.9.2

seaborn: 0.13.2

plotly: 5.5.0

dash: 2.0.0

📄 License
This project is licensed under the MIT License.
