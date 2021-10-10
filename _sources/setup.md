# Setting up an environment

## Set up environment locally using a conda environment file

To get the correct libraries and versions it is recommended that the provided conda environment is used. To create and activate the titanic environment:

1. Download the environment.yml file from https://github.com/MichaelAllen1966/titanic/tree/main/binder

2. Windows -> Open Anaconda prompt. Mac/linux -> Open a terminal

3. Run the following command: `conda env create -f environment.yml`

This will fetch and install the libraries in a conda environment 'titanic'

4. To activate the enviroment run the following command:
    `conda activate titanic`
    
## Set up environment locally manually

1. Create a new environemnt with `conda create -n titanic python=3.8`

2. Activate environment with `conda activate titanic`

3. Install rerquired packages with:

    `conda install pandas=1.3 numpy=1.20 matplotlib=3.4 jupyterlab tensorflow=2.4 scikit-learn=0.24`
    
    `pip install imblearn==0.0 pydot==1.4 graphviz==0.17`
    
## Download files

Jupyter Notebooks may be downloaded individually from the book pages here, or may be downloaded together from https://github.com/MichaelAllen1966/titanic
