[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/talk_pyhep21_lumin/blob/main/Binary_Classification_Signal_versus_Background.ipynb)
<!-- [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5075081.svg)](https://doi.org/10.5281/zenodo.5075081) -->

# An Introduction to LUMIN: A deep learning and data science ecosystem for high-energy physics

**Giles Strong, Originally presented at PyHEP 2021: https://indi.to/WnHcZ**

<!-- YouTube recording: -->

LUMIN is a deep-learning and data-analysis ecosystem for High-Energy Physics. Similar to Keras and fastai it is a wrapper framework for a graph computation library (PyTorch), but includes many useful functions to handle domain-specific requirements and problems. It also intends to provide easy access to state-of-the-art methods, but still be flexible enough for users to inherit from base classes and override methods to meet their own demands.

It has already been used in a diverse range of applications, e.g. HEP searches with DNNs, industry predictive analytics using feature filtering and interpretation, and final-state reconstruction with 3D CNNs and GNNs.

This notebook tutorial aims to introduce new users to how to approach and solve typical supervised classification problems using the package, as well as describe a few of the more advanced features.

GitHub: https://github.com/GilesStrong/lumin
Docs: https://lumin.readthedocs.io/en/stable/?badge=stable


## Usage

### Local installation

- Install using the pip  (`pip install lumin jupyter`).
- Launch jupyter (`jupyter notebook`)
- Open Binary_Classification_Signal_versus_Background.ipynb


## Colab

- Click the Colab badge at the top of the readme, or [here](https://colab.research.google.com/github/GilesStrong/talk_pyhep21_lumin/blob/main/Binary_Classification_Signal_versus_Background.ipynb)
- Change the runtime type to GPU