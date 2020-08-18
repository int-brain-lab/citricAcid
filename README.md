# Citric Acid water as an alternative to water scheduling in behaving mice

Anne Urai, CSHL, 2020

Questions? anne.urai@internationalbrainlab.org



## Instructions for reproducing the data analysis ##

### 1. clone GitHub repo
Clone (first time) or pull (after that) this `citricAcid` repository to a convenient place on your laptop

### 2. install datajoint environment
Create an Anaconda environment (e.g. `djenv`) that will have all your DataJoint things in it. The `iblenv` (https://github.com/int-brain-lab/iblenv) is the easiest way to do so.

Activate that environment, then install DataJoint following these steps: https://tutorials.datajoint.io/setting-up/datajoint-python.html. See https://github.com/int-brain-lab/paper-behavior#obtain-a-datajoint-account-through-ibl-jupyterhub for instructions on how to obtain a DataJoint account.

Install all packages used in IBL: see https://github.com/int-brain-lab/paper-behavior#obtain-a-datajoint-account-through-ibl-jupyterhub.
Make sure you can run Jupyter notebook within conda: `conda install nb_conda_kernels` and `conda install nb_conda`.

### 3. open Jupyter notebook
Notebooks are a nice way to run your code piece by piece and see the results. `source activate djenv`, `jupyter notebook` will open a folder where each notebook will reproduce one ore more figures.
