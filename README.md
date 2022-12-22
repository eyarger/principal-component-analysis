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

### Table of Contents
1.  License --- GNU Affero General Public License v3.0. 
3.  PCA-analysis.pdf --- Full written analysis of this PCA project.
4.  PCA-jupyter-notebook.ipynb --- JupyterNotebook with all code for project.
5.  PCA-notebook-pdf.pdf --- PDF copy of my JupyterNotebook, with all outputs visualized.

### Tools Used
1.  Python
2.  JupyterLab
3.  Matplotlib.pyplot
4.  pandas
5.  numpy
6.  seaborn
7.  missingno
8.  sklearn.preprocessing
9.  sklearn.decomposition

