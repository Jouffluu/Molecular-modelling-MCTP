# Molecular-modelling-MCTP

# Protein Analysis Notebooks

This repository contains a set of Jupyter notebooks for protein analysis. Each notebook is self-contained and includes detailed comments and explanations.

## Notebooks

- `PLDDT.ipynb`: This notebook focuses on the analysis and visualization of per-residue confidence scores (PLDDT) from AlphaFold predictions, providing insights into the reliability of predicted protein structures.
- `PEA.ipynb`: A tool for handling AlphaFold Predicted Aligned Error (PAE) data, this notebook includes classes and functions to load PAE data, generate PAE plots, and save the results.
- `contact-map-pdb.ipynb`: The notebook utilizes Protein Data Bank (PDB) files to generate contact maps for specified monomers and dimers. The generated plots include distance arrays, and each plot is labeled with the corresponding model name.
- `Clustering.ipynb`: This notebook applies clustering algorithms to categorize protein structures into groups based on similarities, facilitating the understanding of structural relationships and common features.
-  `RMSD.ipynb`:Designed to compute the Root Mean Square Deviation (RMSD) of protein structures, this notebook offers a quantitative measure of structural similarity and differences between target and reference structures.
-  `Tica_PCA.ipynb`:Designed to compute PCA and tICA
  
## Dependencies

All Python dependencies are listed in the `requirements.txt` file. You can install them with pip using the following command:

pip install -r requirements.txt


## Data

The data used in these notebooks is hosted on Zenodo. You can download it from the following link: 
https://doi.org/10.5281/zenodo.8190073

## Usage

To run these notebooks, clone the repository, install the dependencies, download the data from Zenodo and start Jupyter:

## License
