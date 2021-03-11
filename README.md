# Analysis and Visualization of Earthquakes
 Between the years 1910-2017 the data analysis and visualization of the earthquake in Turkey obtained from these data.

 For the analysis of earthquakes, data created by various institutions and organizations will be used. These data are stored in a file with the extension ".csv". Inside; Data are stored in the form of earthquake id, date, time, latitude, longitude, city, country, earthquake distance, earthquake depth, earthquake duration, local magnitude (Richter), moment magnitude, surface wave, plane wave magnitude, the largest magnitude except others.

## For Starters:
   First you need to install Anaconda. [Anaconda](https://www.anaconda.com/products/individual).
   
   Start 'Jupyter Notebook' right after the installation. And run the program piece by piece.


## Import:
* import numpy as np
* import pandas as pd
* import matplotlib.pyplot as plt
* import seaborn as sns
* import time
* import datetime
* from datetime import datetime
* import collections
* from collections import Counter
* import os

## Changes:

You must change the location of your files. Fill in the blank.

Original -> "print(os.listdir(\"C://Users//burak\"))\n",

_"print(os.listdir(\"C://    //     \"))\n",_


## Some Code Lines:


* Name of the .csv file to be read and the reading process.

![Reading CSV File](https://user-images.githubusercontent.com/6817125/110784462-c785fc80-827a-11eb-9b1e-f61fd5a6e763.png)

* Column names in the .csv file

![Column Name](https://user-images.githubusercontent.com/6817125/110784825-382d1900-827b-11eb-989f-12b7fde88911.png)



## Visualization:

* In this chart, it is shown that the desired columns are listed from the date the data was started to be stored until 2017.

![Visualization-1](https://user-images.githubusercontent.com/6817125/110785000-70ccf280-827b-11eb-8edf-79ff743a64c4.png)

* The 10 countries with the most earthquakes are shown on the pie slice. In addition, _a=data.country.value_counts()[0:10]_ When we change the location of '10' from the command line, you can list as many cities as you want.

![Country](https://user-images.githubusercontent.com/6817125/110785172-ae318000-827b-11eb-897c-e3aac16eec59.png)
