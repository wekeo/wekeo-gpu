# wekeo-gpu

**wekeo-gpu** is a collection of Python-based code 
designed to provide introductory training on the use 
of the [WEkEO GPUs]('https://help.wekeo.eu/en/articles/7945473-which-are-the-computing-resources-of-the-wekeo-jupyterhub') on the [WEkEO Workspace](https://jupyterhub.prod.wekeo2.eu/).. This module is designed to stand-alone but also forms parts of wider 
WEkEO training activities.

## License
 
This code is licensed under an GPL-3.0 license. 
See file LICENSE.txt for details on the usage and distribution terms.

All product names, logos, and brands are property of their respective owners. 
All company, product and service names used in this website are for 
identification purposes only.
 

## Authors
* [**Anna-Lena Erdmann**](mailto://annalena.erdmann@eumetsat.int) - *Initial development* - [EUMETSAT](http://www.eumetsat.int)
* [**Hugues Sassier**](mailto://hugues.sassier@thalesaleniaspace.com) - *Ollama Notebook* - [Thales Alenia Space](https://www.thalesaleniaspace.com/en)
 
## Getting Started
  
The course is based on [Jupyter notebooks](https://jupyter.org/), which allow
a high-level of interactive learning, as code, text description and 
visualisation is combined in one place. If you have not worked with 
`Jupyter Notebooks` before, you can look at the module 
[Introduction to Python and Project Jupyter](./welcome_to_wekeo_jupyterlab.ipynb) 
to get a short introduction to the WEkEO Jupyter Lab workspace.

### Prerequisites
 
If you are working on a local machine, you will require Jupyter notebook to run this code. We recommend that you install the
latest Anaconda Python distribution for your operating system (https://www.anaconda.com/). 
Anaconda Python distributions include Jupyter Notebook. We recommend setting up an
environment as recommended below, however you may also adapt your current Python 
environment to include the dependencies listed.

nvtop requires a linux operating system. 
 
### Dependencies

| Package   | Version | License      | Link                                                                 |
|-----------|---------|--------------|----------------------------------------------------------------------|
| python    | 3.10.1  | PSF-2.0      | [python.org](https://www.python.org/downloads/release/python-3100/)  |
| ollama    | 0.12.2  | MIT    | [anaconda.org/conda-forge/ollama](https://anaconda.org/conda-forge/ollama)  |
| nvtop   | 3.2.1  | GPL-3.0    | [anaconda.org/conda-forge/nvtop](https://anaconda.org/conda-forge/nvtop)  |
| pytorch  | 2.8.0  | BSD-3-Clause    | [anaconda.org/conda-forge/pytorch](https://anaconda.org/conda-forge/pytorch)  |
