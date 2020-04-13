# Telecom-analysis

**1. Problem Statement**

To understand the user's demographic charactrsatics based on their mobile usage, geolocation and mobile device properties. From this information , data driven marketing, according to the usage and geolocation can be done more efficiently.

**Loading Data

import mysql.connector
import numpy as np                     

import pandas as pd
pd.set_option('mode.chained_assignment', None)      # To suppress pandas warnings.
pd.set_option('display.max_colwidth', -1)           # To display all the data in each column
pd.options.display.max_columns = 50                 # To display every column of the dataset in head()

import warnings
warnings.filterwarnings('ignore')                   # To suppress all the warnings in the notebook.

import matplotlib.pyplot as plt
%matplotlib inline

import seaborn as sns
sns.set(style='whitegrid', font_scale=1.3, color_codes=True)      # To apply seaborn styles to the plots.

import datetime as dt


# import folium
from plotly.offline import init_notebook_mode, iplot
import plotly.graph_objs as go
#import chart_studio.plotly as py
from plotly import tools

init_notebook_mode(connected=True)

![](C:\Users\bbaby\Pictures\Capstone
