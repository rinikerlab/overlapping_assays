# Citation

This repo contains the code and datasets for the publication

    G.A. Landrum, S. Riniker 
    "Combining IC50 or Ki Values From Different Sources is a Source of Significant Noise"
    https://FIXME


# Data and results

## Directories:
- datasets: contains the "max curation" IC50 and Ki data sets exported from ChEMBL32 as well as two intake (https://intake.readthedocs.io/) data catalogs describing the data sets.

## Code

- The notebook `ChEMBL32_OverlappingIC50s-paper.ipynb` contains all the code for generating the results in the paper
- The file `environment.yml` can be used to recreate the conda environment used to do the analysis: `conda env create -f environment.yml`