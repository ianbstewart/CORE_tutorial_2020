# CORE Tutorial 2020

This repository contains the materials required for the tutorial presented at CORE Congress 2020, concerning "Exploratory text analysis for computational social science."
The goal of the tutorial is to showcase some simple text analysis techniques that can reveal insight into computational social science questions, such as the content of fake news.

The code for the tutorial is contained in the notebooks `word_frequency.ipynb`, `topic_modeling.ipynb`, and `word_embeddings.ipynb`, which are hosted on Colab at the following links:

1. `word_frequency.ipynb`: https://colab.research.google.com/drive/1GeB_l0nc_30J3yV9f88NjRrwxM04-KV5
2. `topic_modeling.ipynb`: https://colab.research.google.com/drive/1Cz519-LH0tR2mV0xyy0RlrJiLRfFoB82
3. `word_embeddings.ipynb`: https://colab.research.google.com/drive/1HYZ_6ysD_3Yj_JsDV6WtPM-wad-3bQPz

To use one of the notebooks, open the link and choose "Copy to Drive" to make your own version.
You will need to log into your Google account to do this.

### Instructions to run code locally

You can also run the notebooks locally on your own machine, but be warned that installing all the packages may be difficult without `conda`.

The code is compatible with Python 3.
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
