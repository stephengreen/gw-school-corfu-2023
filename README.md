# GW Parameter Inference with Machine Learning

This tutorial applies simulation-based inference to gravitational wave parameter estimation. It uses simulated data (signal waveforms + noise) to train a neural network to represent the Bayesian posterior.

The tutorial works in a simplified setup, inferring just the two mass parameters for a binary black hole, so it runs in a few minutes on a laptop. The notebook should hopefully serve as a starting point for more advanced applications.

## Getting started

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stephengreen/gw-school-corfu-2023/blob/main/tutorial-Corfu-2023.ipynb)

To get started quickly, run the tutorial in Google Colab by clicking the button above. To run it locally (which may be faster), ensure that you create and activate a Python environment with the required packages. If using `conda`, this can be done with
```
conda create -c conda-forge -n gwml python=3.10 pytorch lalsuite glasflow corner numpy matplotlib jupyterlab
conda activate gwml
```

## References

* [My papers](https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=a%20green%20%2B%20a%20gair%20%2B%20ac%201-%3E10&ui-citation-summary=true) on the topic
* [Dingo](https://github.com/dingo-gw/dingo), a package for GW inference with neural posterior estimation
* [SBI](https://www.mackelab.org/sbi/), a higher-level package for simulation-based inference
