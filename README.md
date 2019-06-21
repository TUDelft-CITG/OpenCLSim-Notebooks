# OpenCLSim Notebooks

This is the repository with examples for the [OpenCLSim](https://github.com/TUDelft-CITG/OpenCLSim) package. 

The package documentation can be found [here](openclsim.readthedocs.io).

## Example notebooks

The benefit of OpenCLSim is the generic set-up. This set-up allows the creation of complex logistical flows. A number of examples are presented in the [notebooks folder](https://github.com/TUDelft-CITG/OpenCLSim-Notebooks/tree/master/notebooks). You can run them locally or as an [Azure notebook](https://notebooks.azure.com/joris-denuijl/projects/openclsim/).

Check the information on how to get started either way.

### Using the notebooks locally

If you wish to use the notebooks on your local drive, use the following code to get started.

``` bash
# Download the package
git clone https://github.com/TUDelft-CITG/OpenCLSim-Notebooks

# Go to the correct folder
cd OpenCLSim-Notebooks

# Install package
pip install -r requirements.txt

# Go to the notebooks foldeer
cd notebooks

# Start jupyter notebooks
jupyter notebook
```

### Using Azure Notebooks

If you wish to run the notebooks using Microsoft Azure, use the following set-up to get started.

1. Create a Microsoft [account](https://docs.microsoft.com/nl-nl/azure/notebooks/quickstart-sign-in-azure-notebooks).
2. Go to the following [Azure Notebooks website](https://notebooks.azure.com/joris-denuijl/projects/OpenCLSim).
3. Clone the project, see [information](https://docs.microsoft.com/nl-nl/azure/notebooks/create-clone-jupyter-notebooks#clone-a-project) on cloning by Microsoft.
4. Start the notebook server.
5. Wait a short while before you run any of the notebooks, the environment takes some time to initialize with the additional packages (such as OpenCLSim and SimPy).
