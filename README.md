# odin-tutorial
This project provides an interactive introduction to the Odin information extraction system, including some example domains.

# Requirements

## Client
You'll need python and the package listed in `requirements.txt`.  

## Server
Additionally, the NLP server requires either 1) `java 8` or 2) `docker`.  

For detailed instructions on starting and running the NLP server, [see this section of the documentation for `py-processors`](http://py-processors.readthedocs.io/en/latest/example.html#running-the-nlp-server).

## Setting up your python environment

I recommend using a `conda` environment, though it isn't required.

`py-processors` (the dependency of this tutorial) is compatible with either  python 3 (recommended) or python 2.7.x.
```
conda create -n odin python=3
source activate odin
```

Install the python dependencies with the following command:

```
pip install -r requirements.txt
```

# Running the notebooks

```
jupyter notebook
```
