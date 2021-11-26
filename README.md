# How Would OHBM SEA-SIG Responsibly Do Reproducible Analysis

## Setup

* Clone the repo:
  ```
  $ git clone git@github.com:sebastientourbier/tutorial_carbonfootprint_neuropipelines.git
  ```

* Install the conda environment with codecarbon, datalad, datalad_containers, jupyter notebook:
  ```
  $ cd tutorial_carbonfootprint_neuropipelines
  $ conda env create -f environment.yml
  ```

* If you are on Mac or Windows, you will need to install the [Intel Power Gadget](https://www.intel.com/content/www/us/en/developer/articles/tool/power-gadget.html) to make codecarbon happy

## Run the notebook

* Activate the conda environment, launch Jupyter Notebook, and open the ipython notebook:
  ```
  $ conda activate neuropipelines-env
  (neuropipelines-env)$ jupyter notebook
  ```
