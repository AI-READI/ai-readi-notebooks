<div align="center">

<img src="https://freesvg.org/img/1653682897science-svgrepo-com.png" alt="logo" width="200" height="auto" />

<br />

<h1> AI-READI Dataset Notebooks </h1>

<p>
Jupyter notebooks that provide examples Python code snippets for working with the AI-READI data
</p>

<br />

<p>
  <a href="https://github.com/AI-READI/template/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/AI-READI/template.svg?style=flat-square" alt="contributors" />
  </a>
  <a href="https://github.com/AI-READI/template/stargazers">
    <img src="https://img.shields.io/github/stars/AI-READI/template.svg?style=flat-square" alt="stars" />
  </a>
  <a href="https://github.com/AI-READI/template/issues/">
    <img src="https://img.shields.io/github/issues/AI-READI/template.svg?style=flat-square" alt="open issues" />
  </a>
  <a href="https://github.com/AI-READI/template/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/AI-READI/template.svg?style=flat-square" alt="license" />
  </a>
</p>
   
<h4
    <a href="https://github.com/AI-READI/ai-readi-dataset-notebooks/issues">Report Bug</a>
  </h4>
</div>

<br />

---

## Description

This repository contains Jupyter notebooks developed by the AI-READI team to provide examples for working with the AI-READI dataset. The dataset is accessible on [FAIRhub](https://doi.org/10.60775/fairhub.1). More details about the dataset are available in the [dataset documentation](https://docs.aireadi.org).

## Standard followed
The overall code is structured according to the [FAIR-BioRS guidelines](https://fair-biors.org/). The Python code in the Jupyter notebooks, located in the `main` folder follow the [PEP8 guidelines](https://peps.python.org/pep-0008). Functions are documented with docstring formatted following [Google's style guide](https://google.github.io/styleguide/pyguide.html#38-comments-and-docstrings). All the dependencies are documented in the [environment.yml](environment.yml) file.

## Using the Jupyter notebooks

### Prerequisites
We recommend using Anaconda to create and manage your development environment and using JupyterLab to run the notebook. All the subsequent instructions are provided assuming you are using [Anaconda (Python 3 version)](https://www.anaconda.com/products/individual) and JupyterLab.

### Clone repo
Clone the repo or download as a zip and extract.

### cd into the code folder

Open Anaconda prompt (Windows) or the system Command line interface then naviguate to the code
```sh
cd. ai-readi-notebooks
```

### Setup conda env
```sh
$ conda env create -f environment.yml
```

### Setup kernel for Jupyter lab
```sh
$ conda activate ai-readi--notebooks
$ conda install ipykernel
$ ipython kernel install --user --name=ai-readi-notebooks
$ conda deactivate
```
### Launch Jupyter lab
Launch Jupyter lab and naviguate to `main` folders to select the notebook you want to use (there is one notebook per data type). Make sure to change the kernel to "ai-readi-notebooks" (e.g., see [here](https://doc.cocalc.com/howto/jupyter-kernel-selection.html#cocalc-s-jupyter-notebook)). We recommend to use the [JupyterLab code formatter](https://github.com/ryantam626/jupyterlab_code_formatter) along with the [Black](https://github.com/psf/black) and [isort](https://github.com/PyCQA/isort) formatters to facilitate compliance with PEP8 if you are editing the notebook.

## Inputs and Outputs

The input of the notebooks are the data files from the AI-READI dataset associated with that notebook. Download the AI-READI dataset from [FAIRhub](https://doi.org/10.60775/fairhub.1) before running the notebooks. 

## Issues and Feedback

To report any issues please open a new issue via the [Issues](https://github.com/AI-READI/ai-readi-notebooks/issues) tab. Provide adequate information (operating system, steps leading to error, screenshots) so we can help you efficiently.

## License
This work is licensed under
[MIT](https://opensource.org/licenses/mit). See [LICENSE](https://github.com/AI-READI/ai-readi-notebooks/blob/main/LICENSE) for more information.

## How to cite

If you are using this software or reusing the source code from this repository for any purpose, please cite as indicated in the [CITATION.cff](CITATION.cff) file.

## Acknowledgements

This project is funded by the NIH under award number 1OT2OD032644. The content is solely the responsibility of the authors and does not necessarily represent the official views of the NIH.

<br />

---

<br />

<div align="center">

<a href="https://aireadi.org">
  <img src="https://github.com/AI-READI/AI-READI-logo/raw/main/logo/png/option2.png" height="200" />
</a>

</div>
