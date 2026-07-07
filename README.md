# PTRA Convolution

A Jupyter notebook for performing **Probabilistic Tsunami Risk Assessment (PTRA)** by convolving tsunami hazard curves with vulnerability functions to compute **Loss Exceedance Curves (LECs)**.

## Features

* Reads tsunami hazard curves and vulnerability models
* Computes conditional loss exceedance probabilities
* Performs hazard–vulnerability convolution
* Generates Loss Exceedance Curves (LECs) for multiple hazard realizations
* Computes and plot mean, 16th, and 84th percentile LECs

## Requirements

* Python 3.10+
* NumPy
* Pandas
* SciPy
* Matplotlib

Install dependencies with:

```bash
pip install numpy pandas scipy matplotlib
```

## Inputs

* `vulnerabilityModel.csv` – vulnerability function (median loss and lognormal uncertainty)
* `perc_hazard_curves_marzamemi.txt` – hazard curve thresholds
* `1000_hazard_curves_marzamemi.txt` – ensemble of tsunami hazard curves

## Outputs

* Loss Exceedance Curves (LECs)
* Mean, 16th, and 84th percentile LECs
* Hazard and LEC plots for visualization and uncertainty analysis

## License
