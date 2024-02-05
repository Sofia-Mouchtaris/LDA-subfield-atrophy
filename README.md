# Repository for analyses related to the manuscript: "Mapping Hippocampal and Thalamic Atrophy in Epilepsy: A 7T MRI Study"

## Running the analyses

We provide a stand-alone Jupyter notebook as a companion to the manuscript. The notebook runs all the analyses required to generate figures and findings in the manuscript.

### Installing the Conda virtual environment

Please make sure you have [Anaconda](https://www.anaconda.com/) installed. After cloning, open the repository folder in a terminal window and type: 
```
conda env create -f environment.yml
```
this will create a new Python virtual environment with all the required libraries

Activate the environment with: 
```
conda activate LDA-subfield-atrophy
```

### Running the Jupyter notebook

In order to run the analysis, clone this repository and install the conda virtual environment. Open the Jupyter Notebook `manuscript_companion.ipynb` and execute the analyses from there. If the conda environment was setup appropriately, everything should run correctly.
