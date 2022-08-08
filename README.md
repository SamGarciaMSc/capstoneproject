
# My Capstone Site

https://sammygfish.github.io/capstoneproject/

## Project Introduction

This project is aimed at music funds or any other music copyright exploiter (including songwriters) hoping to refine their process for categorising songs into genres or categories, that in turn drive value.

## Notebooks:
1. Loading, Cleaning and EDA
2. Preprocessing
3. Modeling - Supervised Learning Pipelines
4. Modeling -  Unsupervised Learning, Clustering
5. Findings - Project Summarisation

6.a. Appendix Notebook First Pass Data Investigation and Cleaning
6.b. Appendix Notebook First Pass Feature Selection and Data Transformation
6.c. Appendix Notebook First Pass Unsupervised Learning - Clustering
6.d. - Appendix Notebook - Aborted Spotify API Data
6.e . Appendix Notebook - Discarded Dataset Investigation - Increase and Diversify Datapoints
capstone_functions


**Business Question**
Can we predict a song's popularity (and therefore value) based on its attributes

This is a limited measurement without access to more granular information such as geographical consumption metrics, social media penetration, etc.

We will work on a starter model focusing initially on song attribute clustering and genre analysis with a view to further development in the future to layer on value metrics, given access to the more granular information mentioned above and below.

**Creating a tool that can classify any given song into a genre or attribute-based cluster is a good first step in this direction. Which leads us to the Machine Learning Question:**

**Machine Learning Question**
Can we derive song FEATURE PROFILES (by inspecting the song's audio attributes derived by Spotify) and ascribe VALUE to individual song features or FEATURE PROFILES

Often, songs are given a genre subjectively by music managers' opinion or songs carry genres from the Artists' genre identity, Developing an in-house model for categorising genre based on attributes, then layering on a popularity or value measure, can be of value particularly when tailored for use alongside private data held by the song copyright owners.

- [The dataset is here](https://www.kaggle.com/datasets/maltegrosse/8-m-spotify-tracks-genre-audio-features)

## Environment
See requierments.txt - this project can be run on a base anaconda environment with the following additional installations:
# $ conda create -n capstone python=3.8 numpy pandas matplotlib seaborn jupyter requests scipy lxml
# $pip install xgboost==1.1.1
# $pip install qgrid
# $pip install pivottablejs
# $conda install -c conda-forge spotipy
channels:
  - defaults
dependencies:
  - conda
  - python=3.9
  - menuinst
  - console_shortcut
  - powershell_shortcut
  - conda-env
  - conda-build
  - conda-verify
  - _ipyw_jlab_nb_ext_conf
  - anaconda
  - anaconda-navigator==2.2.0
  - navigator-updater
  - selenium
  - pytesseract=0.3.7
  - jupyter
  - joblib
  - pandasgui
  - pyqt5-sip
  - pyqtwebengine
  - spotipy
(base)