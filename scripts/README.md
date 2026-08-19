# Scripts Directory

This folder contains Python automation and scientific computing scripts used across both project tracks.

## Core Dependencies
* Python 3.x
* `numpy`
* `scipy` (specifically `scipy.stats.qmc.LatinHypercube` for sampling)
* `pandas`
* `matplotlib`

## Script Modules
* `lhs_sampler.py`: Generates the structured Latin Hypercube Sampling matrix across the standard operating envelope ($U_\infty$, $\theta_{pitch}$, $\lambda$).
* `data_processor.py`: Cleans, formats, and structures simulation outputs into `dataset.csv` for Track B consumption.