**[contents](#Contents) | [setup](#Setup) | [running the notebooks](#running-the-notebooks) | [issues](#issues)**

# A-ERT
Notebook to support the publication *Employing Automated Electrical Resistivity Tomography for detecting short- and long-term changes in permafrost and active layer dynamics in the Maritime Antarctic* (Farzamian et al., submitted to The Cryosphere)

## Contents

This repository contains:

1. [notebook for data processing](./data_processing_AERT.ipynb): This notebook contains code for automated filtering and inversion of large A-ERT datasets, as well as useful plotting tools.
2. [data files](./data_AERT): This folder contains the A-ERT data files, including raw input data, inverted data, and site data (probed thaw layer depths, climate data, and borehole data).
 
## Setup

Here are step-by-step instructions for running these notebooks locally on your machine:

Install Python. You can use [anaconda](https://www.anaconda.com/download/) for this.

Clone this repository by running the following in your command line:

```
git clone https://github.com/teddiherring/AERT
```

Next, `cd` into the directory you just created:

```
cd AERT
```

You can use the provided conda environment to set up the necessary software packages:

```
conda env create -f environment.yml
conda activate aert
```

Next, running the following command

```
jupyter notebook
```

will open a Jupyter notebook in your web browser. You can now open the data processing notebook and start running the code!

## Running the notebooks

You can run each cell in the notebook individually by pressing  `shift + enter`, or you can run the entire notebook by selecting `Cell`, `Run All` in the toolbar.

## Issues

Please [make an issue](https://github.com/teddiherring/AERT/issues) if you encounter any problems while trying to run the notebooks.
