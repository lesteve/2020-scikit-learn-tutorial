# scikit-learn tutorial

You can run the notebooks in a binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lesteve/2020-scikit-learn-tutorial/master)

## Getting started

The course uses Python 3 and some data analysis packages such as Numpy, Pandas,
scikit-learn, and matplotlib.

### Install Miniconda

**This step is only necessary if you don't have conda installed already**:

- download the Miniconda installer for your OS [here](https://docs.conda.io/en/latest/miniconda.html)
- run the installer following the instructions
  [here](https://conda.io/projects/conda/en/latest/user-guide/install/index.html#regular-installation)
  depending on your OS.

### Create conda environment

```sh
# Clone this repo
git clone https://github.com/lesteve/2020-scikit-learn-tutorial
cd 2020-scikit-learn-tutorial
# Create a conda environment with the required packages for this tutorial:
conda env create -f environment.yml
```

### Check your install 

We **strongly recommend** you to open and execute the script located at the
root of this repository to make sure you have the necessary packages installed:

```sh
# Activate your conda environment
conda activate scikit-learn-tutorial
python check_env.py
```

### Run Jupyter notebooks locally

```sh
# Activate your conda environment
conda activate scikit-learn-tutorial
jupyter notebook
```

The Jupyter notebooks are located in the `notebooks` folder.
