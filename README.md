# <img alt="amlearn" src="docs_rst/_static/amlearn_logo.png" width="300">
Machine Learning package for amorphous materials(Working in Progress).

We integrate Fortran90 with Python (using f2py) to achieve combination of the
flexibility and fast-computation (>10x times faster than pure Python) of features. Please see examples
in the short-range ordering (SRO) and medium-range ordering (MRO) representations
in the featurizers folder. The SRO and MRO representation are based on a recent
paper by Qi Wang and Anubhav Jain (to be published).

Wrapper classes and utility functions for featurizers powered by matminer/amp and machine
learning algorithms supported by scikit-learn are also included.


------------------


## Installation

Before installing Amlearn, please install numpy (version 1.7.0 or greater) first.

We recommend use the conda install.

```sh
conda install numpy
```

or you can find numpy install guide from:

- [Numpy installation instructions](https://www.scipy.org/install.html).


Then, you can install Amlearn itself. There are two ways to install Keras:

- **Install Amlearn from PyPI (recommended):**

```sh
pip install amlearn
```


- **Alternatively: install Amlearn from the GitHub source:**

First, clone Keras using `git`:

```sh
git clone https://github.com/Qi-max/amlearn
```

 Then, `cd` to the Amlearn folder and run the install command:
```sh
cd amlearn
sudo python setup.py install
```

------------------
