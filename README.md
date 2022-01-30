# funding

Uncovering funding trends in private capital.

## Pre-requisites

We use Poetry for complete Python dependency management and exact reproducability.
However, you also require Java installation, together with the Mallet topic
modelling package, in order to perform extremely fast LDA posterior estimation.
The exact pre-requisites are listed below:

* [pyenv](https://github.com/pyenv/pyenv) with __>= Python 3.6__
* [Poetry](https://python-poetry.org/docs/#installation)
* [Java JRE](https://docs.oracle.com/goldengate/1212/gg-winux/GDRAD/java.htm)
* [MALLET 202108](https://github.com/mimno/Mallet/releases)

## Usage

Once all the pre-requisites are met, run the following:

```
poetry install
poetry shell
jupyter notebook funding.ipynb
```