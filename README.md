# titanic
Titanic machine learning Jupyter Book.

For book go to: 
https://michaelallen1966.github.io/titanic/front_page.html

## Run on Binder or Colab

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MichaelAllen1966/titanic/main)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MichaelAllen1966/titanic/)


## Set up environment locally using the environment file

To get the correct libraries and versions it is recommended that the provided conda environment is used. To create and activate the titanic environment:


1. Windows -> Open Anaconda prompt. Mac/linux -> Open a terminal

2. Navigate to the /binder directory

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
