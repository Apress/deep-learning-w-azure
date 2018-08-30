# Apress Source Code

This repository accompanies [*Deep Learning with Azure*](https://www.apress.com/9781484236789) by Mathew Salvaris, Danielle Dean, Wee Hyong Tok (Apress, 2018). It contains the notebook examples from the book. The notebooks are broken up into their respective chapters.

* [Chapter 6](Chapter06): Convolutional Neural Networks
* [Chapter 7](Chapter07): Recurrent Neural Networks
* [Chapter 9](Chapter09): Training AI models

[comment]: #cover
![Cover image](images/9781484236789.jpg)

Download the files as a zip using the green button, or clone the repository to your machine using Git.

## Prerequisites
* PC or VM with Linux (Ubuntu). We suggest using an [Azure Linux DSVM](https://azuremarketplace.microsoft.com/en-gb/marketplace/apps/microsoft-ads.linux-data-science-vm-ubuntu)
* Basic knowledge of [anaconda environments](https://conda.io/docs/user-guide/tasks/manage-environments.html)
* Basic knowledge of [Jupyter notebooks](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html)

## Setup
Please create a conda environment that will satisfy all the Python dependencies required by the notebooks. We have supplied a YAML file with the necessary dependencies [here](environment.yml)

You can create a conda environment using the command below:
```bash
conda env create -f environment.yml
```

Once the environment has been created successfully activate it:
```bash
source activate azureai
```

With the environment activated start the Jupyter notebook server:
```bash
jupyter notebook --ip=* --port=9999 --no-browser
```

The above command tells Jupyter notebook to accept connections from all IPs and listen on port 9999. If you are using a different port or wish to restrict the IPs adjust accordingly.

To access the Jupyter notebook simply point your web-browser to the appropriate IP on port 9999

## Releases

Release v1.0 corresponds to the code in the published book, without corrections or updates.

## Contributions

See the file [Contributing.md](Contributing.md) for more information on how you can contribute to this repository.