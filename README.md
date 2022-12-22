[eric-yarger.com](http://www.eric-yarger.com)

## principal-component-analysis
## Using Python to clean, explore, and identify PCs in dataset.

### Abstract
This repository contains a project I researched and analyzed on a medical dataset.
The goal of this analysis was to decide on the optimal number of Principal Components (PCs)
that explain the majority of readmission rates at our hospital.

### Process
1.  The data .csv file is loaded into a JupyterNotebook.
2.  Data is explored, analyzed, and preprocessed.
3.  Data is cleaned, outliers > 3 standard deviations removed from dataset.
4.  PCA is performed to identify the number of applicable principal components.
5.  PCs with eigenvalues > 1 are considered applicable.
6.   
### Table of Contents
1.  License --- GNU Affero General Public License v3.0. 
3.  PCA-analysis.pdf --- Full written analysis of this PCA project.
4.  PCA-jupyter-notebook.ipynb --- JupyterNotebook with all code for project.
5.  PCA-notebook-pdf.pdf --- PDF copy of my JupyterNotebook, with all outputs visualized.

### Tools Used
Python
JupyterLab
Matplotlib.pyplot
pandas
numpy
seaborn
missingno
sklearn.preprocessing
sklearn.decomposition
