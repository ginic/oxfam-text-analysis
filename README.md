# Oxfam and UMass Amherst Collaboration at AI for Social Good, Dagstuhl
This repository is one outcome of the hackathon at the Dagstuhl AI for Social Good conference in Feburary 2024. 


# Getting started
## Installing Dependencies and Packages
This repository was created from the [UMass Amherst Center for Data Science python project template](https://github.com/UMassCDS/PythonProjectTemplate). If you have questions about the package file structure or python dependency, installation there are more details at [this link](https://github.com/UMassCDS/PythonProjectTemplate).
Use these steps for setting up a development environment to install and work with this code:
1) Set up a Python 3 virtual environment using [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html#) or [Virtualenv](https://virtualenv.pypa.io/en/latest/index.html). Read [Python Virtual Environments: A Primer](https://realpython.com/python-virtual-environments-a-primer/#the-virtualenv-project) for details on how to get started with virtual environments and why you need them.
2) Activate your virtual environment.

3) Install the package.
	- If you want to just use the scripts and package features, install the project by running `pip install .` from the root directory.
	- If you will be changing the code and running tests, you can install it by running `pip install -e .`. The `-e/--editable` flag means local changes to the project code will always be available with the package is imported. You wouldn't use this in production, but it's useful for development.

## Running Jupyter Notebooks for Exploration
The initial exploration from the hackathon is in `notebooks/exploration.ipynb`
After you have installed the dependencies, you can run `jupyter notebook` or `jupyter lab`, then open `exploration.ipynb`. See the [jupyter documentation](https://docs.jupyter.org/en/latest/) for more details.