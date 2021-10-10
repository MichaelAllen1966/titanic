# Setting up an environment

## Set up environment locally using a conda environment file

To get the correct libraries and versions it is recommended that the provided conda environment is used. To create and activate the titanic environment:

1. 2Download the environment.yml file from https://github.com/MichaelAllen1966/titanic/tree/main/binder

2. Windows -> Open Anaconda prompt. Mac/linux -> Open a terminal

3. Run the following command: `conda env create -f environment.yml`

This will fetch and install the libraries in a conda environment 'titanic'

4. To activate the enviroment run the following command:
    `conda activate titanic`
    
## Set up environment locally manually

1. Create a new environemnt with `conda create -n titanic python=3.8`

2. Activate environment with `conda activate titanic`

3. Install rerquired packages with:
    `conda install pandas numpy matplotlib jupyterlab tensorflow scikit-learn`
    `pip install imblearn pydot graphviz`
    
## Download files

Jupyter Notebooks may be downloaded individually from the book pages here, or may be downloaded together from https://github.com/MichaelAllen1966/titanic
