# Artificial Reef Complexity
Script (Pyhton &amp; R) for the research paper **Unleashing the Potential of Artificial Reefs Design:  A Purpose-Driven Evaluation of Structural Complexity**

You'll find here 3 scripts :
* `Extraction_Of_Parameters & Complexity_Indexes_Computation`Python script to extract parameters from 3D CAD models (STL format) and compute complexity indexes (except fractal dimension).  
  versions: .py, ipynb, .htlm
* `Fractal_Dimension_Computation` R script to compute fractal dimension on point clouds extracted from 3D CAD models.  
  versions: .Rmd, .htlm
* `MFA_Multiscale-Complexity-Index` R script to compute the Multiscale Complexity Indexes (MCI) with the dataframe "df_compleixty_indexes.csv" available on Zenodo: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8055070.svg)](https://doi.org/10.5281/zenodo.8055070)
  
  versions: .Rmd, .htlm

PS1: your STL files must be watertight models; otherwise, the computation won't be comparable with the models from the study.  
PS2: 3D CAD models and point clouds are available on Zenodo to test the script:
* STL [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8048071.svg)](https://doi.org/10.5281/zenodo.8048071)
* TXT [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8048122.svg)](https://doi.org/10.5281/zenodo.8048122)
