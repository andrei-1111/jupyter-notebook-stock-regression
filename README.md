

### Usage
The jupyter notebook reads a `.csv` stock data and displays graphs of the regression models.

- Download an updated historical data from [Yahoo Finance](https://finance.yahoo.com/quote/AAPL/history?p=AAPL)
- Run the jupyter notebook

### Base system requirements
- python 3
- [pyenv](https://github.com/pyenv/pyenv#basic-github-checkout)
- [pipenv](https://github.com/pypa/pipenv#installation)
- [jupyter](https://jupyter.readthedocs.io/en/latest/install.html#alternative-for-experienced-python-users-installing-jupyter-with-pip)

### Running the Jupyter notebook
``` bash
# Create env with python 3.6
pipenv --python 3.6
# Install requirements from Pipfile
pipenv install
# Run the notebook
pipenv run jupter notebook
```
