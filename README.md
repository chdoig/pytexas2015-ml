# README

Beginner's Guide to Machine Learning Competitions, PyTexas 2015, Tutorial

# Setup

```
git clone https://github.com/chdoig/pytexas2015-ml.git
cd pytexas2015-ml
```

- **Option A: Anaconda**

If you don't have Anaconda installed, you can install it from [here](https://store.continuum.io/cshop/anaconda/).

If you already have Anaconda installed, make sure to update both conda and the dependencies 
to the latest versions, by running:

```
conda update conda
conda install pandas
conda install numpy
conda install scikit-learn
conda install jupyter
conda install matplotlib
conda install seaborn
conda install ggplot
```

- **Option B: Miniconda or Conda Environments**

If you want one the following:

- a lightweight alternative to Anaconda, you can install Miniconda from 
[here](http://conda.pydata.org/miniconda.html). 

or 

- isolate this tutorial dependencies from your default Anaconda by using conda environments.

Follow this commands after cloning this repository:

```
cd pytexas2015-ml
conda env create
```

If you are running Linux or OS X run:

```
source activate pytexas-ml
```

If you are running Windows, run:

```
activate pytexas-ml
```

- **Option C: Alternative setup**

Install the following dependencies with the package manager of your choice, e.g. pip.

Dependencies:
    - pandas
    - numpy
    - scikit-learn
    - jupyter
    - matplotlib
    - seaborn
    - ggplot

# Competition

https://www.kaggle.com/c/word2vec-nlp-tutorial/data

# Data

Download the datasets from here:

- [labeledTrainData.tsv.zip](https://s3-eu-west-1.amazonaws.com/europython-tutorial/labeledTrainData.tsv.zip) ~13MB
- [testData.tsv.zip](https://s3-eu-west-1.amazonaws.com/europython-tutorial/testData.tsv.zip) ~13MB
