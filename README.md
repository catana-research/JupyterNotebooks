# JupyterNotebooks

This repository contains Jupyter Notebooks with useful examples.

## Start a server using a batch script

To start a Jupyter Lab session from a batch script using Anaconda3 call:

```
call ANACONDA3_DIR\Scripts\activate.bat ANACONDA3_DIR
call conda activate CONDA_ENV
call jupyter lab --notebook-dir=JUPYTER_NOTEBOOKS_DIR
```

Where `ANACONDA3_DIR` is your Anaconda3 installation directory, `CONDA_ENV` is your chosen Conda environment and `JUPYTER_NOTEBOOKS_DIR` is the location of your saved notebooks.
