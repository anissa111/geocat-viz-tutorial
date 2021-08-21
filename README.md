# Plotting With GeoCAT Tutorial

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/anissa111/plotting-with-geocat-tutorial/HEAD?urlpath=lab)

This repository contains materials for the Plotting with GeoCAT tutorial

## Running the tutorial

There are two different ways in which you can set up and go through the tutorial materials. Both of which are outlined in the table below.

|    Method     |                                                          Setup                                                           | Description                                                                                                                                                                                                             |
| :-----------: | :----------------------------------------------------------------------------------------------------------------------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|    Binder     | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/anissa111/plotting-with-geocat-tutorial/HEAD?urlpath=lab) | Run the tutorial notebooks on mybinder.org without installing anything locally (suggested for Windows users).                                                                                                                                         |
| Local install |                                     [Instructions](#Local-installation-instructions)                                     | Download the tutorial notebooks and install the necessary packages (via `conda`) locally. Setting things up locally can take a few minutes, so we recommend going through the installation steps prior to the tutorial. |


## Local installation instructions

### 1. Clone the repository

First clone this repository to your local machine via:

```
git clone git clone https://github.com/anissa111/plotting-with-geocat-tutorial
```

### 2. Create a conda environment

Navigate to the `plotting-with-geocat-tutorial/` directory and create a new conda environment with the required
packages via:

```terminal
cd plotting-with-geocat-tutorial
conda env create --file environment.yml
```

### 3. Activate the environment

Next, activate the environment with:

```
conda activate geocat-viz-tutorial
```

### 4. Launch JupyterLab

Finally, launch JupyterLab with:

```
jupyter lab
```
