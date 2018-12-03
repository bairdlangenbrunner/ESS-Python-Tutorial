# Today (week 2):  Opening Python, Jupyter Notebooks, and some very basic




# Today (week 2):  useful libraries to explore

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

# Do this before the end of class TODAY :computer:
* Install ```xarray``` and ```cartopy``` in your anaconda installation by typing in a new __terminal shell__:
```
conda install xarray
conda install -c conda-forge cartopy
```

* __NOTE:__  If conda doesn't recognize the xarray or cartopy library, try the conda-forge channel (community-driven packages), INSTEAD:
```
conda install -c conda-forge xarray
conda install -c conda-forge cartopy
```
Output like that below should come up; choose ```y``` (yes):

```
Fetching package metadata ...........
Solving package specifications: .

Package plan for installation in environment /Users/baird/anaconda/envs/nco_stable:

The following NEW packages will be INSTALLED:

n
```

# Do this before next week :earth_americas:
* Install a ```UVCDAT``` environment at the terminal shell:
```
conda create -n ENVT_NAME uvcdat -c conda-forge -c uvcdat
source activate ENVT_NAME
```
* In ```ENVT_NAME```, choose an environment name that you can remember, like ```myuvcdat```, ```uvcdat_env```, or ```uvcdat_stable```.  Remember you can list all of your conda environments by typing ```conda info --envs``` at the command line.
