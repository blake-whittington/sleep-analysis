# COMP30780 Repository

This repository contains the code for our project "How Not To Put a Nation To Sleep".


# "How Not To Put a Nation To Sleep" Repository 2022

Collaborators: Blake Whittington & Gabriele Spiridaviciute\

Language:
Python (3.9.7)

IDEs Used:
Visual Studio Code, DataSpell, JupyterLab and Jupyter Notebook.


# File Reference:
|Topic                  | File                                                                                                                 | Description |  
| ----------------      | ----                                                                                                                 | ----------- |
|Data Preparation       | [0001_prep_oecd.ipynb](0000_data_prep/0001_prep_oecd.ipynb)                                                          | Load and clean OECD Time Use Data For RQ1.|
|                       | [0002_prep_economic_data.ipynb](0000_data_prep/0002_prep_economic_data.ipynb)                                        | Load and clean Time Americans Spent Sleeping Data For RQ2.|
|                       | [0003_prep_13_data.ipynb](0000_data_prep/0003_prep_13_data.ipynb)                                                    | Load and clean 2013 Survey Poll Data For RQ3.|
|RQ1                    | [1001_men_women_comparison.ipynb](1000_RQ1/1001_men_women_comparison.ipynb)                                          | Comparing time use data from around the world - looking at the differneces between genders.|
|                       | [1002_world_map.ipynb](1000_RQ1/1002_world_map.ipynb)                                                                |Create a choropleth to show the difference between sleep time around the world.|
|                       | [1003_general_analysis.ipynb](1000_RQ1/1003_general_analysis.ipynb)                                                  | Taking a look at how time use differs around the world and what America should focus on|
|RQ2                    | [2001_load_bls_tass_sleep_data.ipynb](2000_RQ2/2001_load_bls_tass_sleep_data.ipynb)                                      | Looking at how changes in Inflation, Unemployment and GDP affect sleep time in America 2003-2019|
|                       | [2002_economic_factors_sleep.ipynb](2000_RQ2/2002_economic_factors_sleep.ipynb)                                      | Looking at how changes in Inflation, Unemployment and GDP affect sleep time in America 2003-2019|
|RQ3 - General Analysis | [3011_general_health_sleep_13_poll.ipynb](3000_RQ3/3011_general_health_sleep_13_poll.ipynb)    | A general analysis of how Americans rate their health and sleep|
|                       | [3012_caffeine_analysis.ipynb](3000_RQ3/3012_caffeine_analysis.ipynb)                          | Looking at the influence of caffeine on sleep|
|                       | [3013_tobacco_analysis.ipynb](3000_RQ3/3013_tobacco_analysis.ipynb)                            | Looking at the influence of tobacco on health|
|                       | [3014_alcohol_analysis.ipynb](3000_RQ3/3014_alcohol_analysis.ipynb)                            | Looking at the influence of alcohol on health and sleep|
|RQ3 - Cluster Analysis | [3021_kmodes_pca_clustering.ipynb](3000_RQ3/3021_kmodes_pca_clustering.ipynb)                  | Using KMODES algorithm and PCA to create clusters of surveyors|
|                       | [3022_cluster_desirability_analysis.ipynb](3000_RQ3/3022_cluster_desirability_analysis.ipynb)  | Choosing the most ideal clusters|
|                       | [3023_initial_cluster_results.ipynb](3000_RQ3/3023_initial_cluster_results.ipynb)              | Initial analysis of how many clusters suffer fro substance abuse|
|                       | [3024_clusters_and_substances_.ipynb](3000_RQ3/3020_cluster_analysis/3024_clusters_and_substances_.ipynb)            | In depth look at whether or not our cluster's health and ratings correspond with their substance usage habits|
|Data Files             | [data_file](data_file)                                                                                               | Various Data Files We Used |
|Future Work            | [future_work](future_work)                                                                                           | Contains data and notebooks we hope to work on in the future|

# Imports Used In Our Project:
*  import pandas as pd (Version 1.4.2)
*  import numpy as np (Version 1.20.3)
*  import os
*  import glob
*  import matplotlib.pyplot as plt (Version 3.5.1)
*  import datetime
*  import seaborn as sns (Version 0.11.2)
*  import geopandas as gpd
*  import json
*  from bokeh.io import output_notebook
*  from bokeh.models import GeoJSONDataSource, HoverTool,LinearColorMapper,ColorBar, Label, LabelSet
*  from bokeh.io import show, export_png
*  from bokeh.plotting import figure
*  import matplotlib.ticker as mtick
*  from matplotlib.lines import Line2D
*  import plotly.graph_objects as go #allows to make interactive graphs
*  import math 
*  from csv import reader

# Sources:
* https://www.sleephealthjournal.org/content/sleepinamerica
* https://stats.oecd.org/Index.aspx?datasetcode=TIME_USE
* https://data.world/makeovermonday/2019w23
* https://www.niaaa.nih.gov/alcohol-health/overview-alcohol-consumption/moderate-binge-drinking
* https://www.bbcgoodfood.com/howto/guide/spotlight-caffeine
* https://towardsdatascience.com/clustering-datasets-having-both-numerical-and-categorical-variables-ed91cdca0677
* https://www.analyticsvidhya.com/blog/2021/06/kmodes-clustering-algorithm-for-categorical-data/#:~:text=KModes%20clustering%20is%20one%20ofsimilar%20our%20data%20points%20are.
* https://medium.com/analytics-vidhya/the-ultimate-guide-for-clustering-mixed-data-1eefa0b4743b
* https://www.kaggle.com/code/ashydv/bank-customer-clustering-k-modes-clustering/notebook
* https://www.kaggle.com/code/teejmahal20/clustering-categorical-data-k-modes-cat-ii/notebook


Created in completion for COMP30780: Data Science in Practice at University College Dublin
