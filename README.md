# PyFirenze Meetup

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jackdbd/python-firenze-meetup-2020-02-06/master)

![An animated GIF showing a map of food inspections in San Francisco in 2013-2016](https://raw.githubusercontent.com/jackdbd/python-firenze-meetup-2020-02-06/master/images/high-risk-vermin-infestation-sf.gif "High risk of vermin infestation in San Francisco, 2013-2016")

![A map of food inspections in San Francisco in 2016](https://raw.githubusercontent.com/jackdbd/python-firenze-meetup-2020-02-06/master/images/food-inspections-in-sf.png "Number of food inspections in San Francisco, 2016 (aggregated by ZIP code)")

## Installation

If you don't already have it, download [Anaconda](https://www.anaconda.com/distribution/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html).

Create the Python virtual environment from the `environment.yml` file:

```sh
conda env create -f environment.yml
```

## Run the notebook

Activate the virtual environment and run the jupyter notebook server:

```sh
conda activate pyfirenze37
jupyter notebook
```

To deactivate the virtual environment, run `conda deactivate` from this repository root.
