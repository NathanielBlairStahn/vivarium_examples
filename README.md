# Vivarium Examples
Examples of simulations built with [Vivarium](https://vivarium.readthedocs.io/en/latest/index.html), from the [Vivarium Tutorials](https://vivarium.readthedocs.io/en/latest/tutorials/index.html).


# Environment Setup

## Mac OS X

```bash
# Create a new conda environment named `vivarium` with the ipython kernel installed
conda create --name vivarium ipykernel
# Activate the new environment
source activate vivarium
# Use pip to install the vivarium module
pip install vivarium
# Install the kernel for the new environment (for the current user) so Jupyter will detect it
ipython kernel install --user --name vivarium --display-name "Vivarium (Python 3.7)"
```

Now, after following the instructions in the [Getting Started Tutorial](https://vivarium.readthedocs.io/en/latest/tutorials/getting_started.html), from the base directory `~/code/vivarium_examples` run the command

```bash
# Install the `vivarium_examples` package
python setup.py develop
```
