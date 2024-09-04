
## Introduction

Probabilistic Programming allows for automatic Bayesian inference on user-defined probabilistic models, providing a flexible and powerful toolset for data analysis and prediction. This project aims to demonstrate how to set up an environment and use PyMC to perform Bayesian inference with specific probabilistic models. PyMC is a Python library for probabilistic programming that enables users to specify rich statistical models directly in Python and leverage advanced sampling algorithms for inference.

In this project, we will explore:

- The half-normal distribution, which is a normal distribution bounded at zero. This distribution can be useful in scenarios where only positive values make sense.
- Zero-mean normal priors. This corresponds to weak information about the true values of the parameters, allowing for a more data-driven inference process.

This guide will walk you through the necessary installations and environment setup to get started with PyMC.

## Setup

### Installations

To ensure a smooth setup, follow the steps below to create and configure your environment:

1. Create a new conda environment with the PyMC package:
    ```bash
    conda create -c conda-forge -n pymc_env "pymc>=5"
    ```

2. Install the m2w64-toolchain, which is required for compiling certain dependencies:
    ```bash
    conda install m2w64-toolchain
    ```

3. Install the IPython kernel to enable Jupyter Notebook support:
    ```bash
    conda install ipykernel
    ```

### Activate Environment

Once the installations are complete, activate the newly created environment:

```bash
conda activate pymc_env
```

You are now ready to start developing and running your probabilistic models using PyMC.

