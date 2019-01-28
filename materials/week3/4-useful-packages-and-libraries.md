# Useful Python packages and libraries

* __numpy:__ numerical python, ```import numpy``` or ```import numpy as np```
* __scipy:__ scientific python, ```import scipy``` or ```import scipy as sp```
* __matplotlib.pyplot:__ mathematical plotting library, ```import matplotlib.pyplot as plt```
* __pandas:__ statistics and econometrics library, "**pan**el **da**ta", ```import pandas``` or ```import pandas as pd```
  * Good for two-dimensional data like csv or txt files
  * Also great for handling dates
* __cartopy:__ cartographic library for python, ```import cartopy```
* __xarray:__ coordinate-referenced data set library (i.e., NetCDF tool), ```import xarray```
  * Kind of like pandas on steroids
  * Stephan will cover __xarray__ in much more detail in week 4

__If you try to import a library that is not recognized:__
1. Check the spelling and case of the LeTtErS
2. Make sure you _have_ it installed by looking for it in the output of ```conda list``` from the terminal shell
3. If it's not there, install it via:

```conda install PACKAGE_NAME```

or

```conda install -c conda-forge PACKAGE_NAME```
