## Stock prediction

We aim to predict the stock market prices from apple, using RNN models.

To install the project you need to install miniconda locally then you need to do the following actions:

minicoda source: https://docs.anaconda.com/free/miniconda/miniconda-install

Create the conda environment - this will create an environment based on what you have in 'environment.yml' file command: conda env create -f environment.yml

Activate the environment command: conda activate 'env-name'

Optionally you can export your dependencies to an external requirements.txt file command: conda list --export > requirements.txt

To update dependencies use the update command and --prune flag to remove all other dependencies that are not longer defined in the .yml file command: conda env update -f environment.yml --prune

For this project I named my env: stock-prediction-env and I used conda to activate it using the following command: command: conda activate stock-prediction-env