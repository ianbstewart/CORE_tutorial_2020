# CORE Tutorial 2020

This repository contains the materials required for the tutorial presented at CORE Congress 2020, concerning "Exploratory text analysis for computational social science."
The goal of the tutorial is to showcase some simple text analysis techniques that can reveal insight into computational social science questions, such as the content of fake news.

The code for the tutorial is contained in the main notebook `CORE_tutorial.ipynb`. 
We assume that you have installed Python on your machine and are familiar with installing packages using `pip` or a self-contained environment like `anaconda`.

Before running the Jupyter notebooks, please install all necessary packages and data (~ 220 MB) in your environment by opening the command line and issuing the following commands.
Note that the download may take from 5-30 minutes depending on your download speed.

Linux:
```
pip install -r requirements.txt
wget https://bitbucket.org/istewart6/core_tutorial_2020/raw/9feab1699d48005d9631f277771d91b2075d1256/data.zip . 
unzip data.zip
```

Mac:
```
pip install -r requirements.txt
curl https://bitbucket.org/istewart6/core_tutorial_2020/raw/9feab1699d48005d9631f277771d91b2075d1256/data.zip -o data.zip
unzip data.zip
```

Next, launch Jupyter locally to start using the notebooks:

```
jupyter-notebook .
```
