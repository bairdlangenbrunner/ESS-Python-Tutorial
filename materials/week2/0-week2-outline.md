# What Python library can I use to...

* ...manipulate large matrices/arrays, and do statistics?
  * use [**numpy**](http://www.numpy.org/) and [**scipy**](https://www.scipy.org/)
  * install via: `conda install numpy scipy` *(already on Anaconda)*
* ...make a plot?
  * use [**matplotlib.pyplot**](https://matplotlib.org/tutorials/introductory/pyplot.html)
  * install via:  `conda install matplotlib` *(already on Anaconda)*
* ...open a csv, txt, or tab-delimited file?
  * use [**pandas**](https://pandas.pydata.org/)
  * install via:  `conda install pandas` *(already on Anaconda)*
* ...open a NetCDF file?
  * use [**xarray**](http://xarray.pydata.org/en/stable/)
  * install via:  `conda install xarray`
* ...plot geographical maps with data on them?
  * use [**cartopy**](https://scitools.org.uk/cartopy/docs/latest/)
  * install via:  `conda install -c conda-forge cartopy`
* ...use shapefiles to plot physical or cultural boundaries?
  * use [**geopandas**](https://geopandas.readthedocs.io/en/latest/index.html) and [**shapely**](https://shapely.readthedocs.io/en/stable/manual.html)
  * install via:  `conda install geopandas` *(will install shapely, too)*

---

# How can I teach some of this to myself?

The [Software Carpentry](https://software-carpentry.org/lessons/) and [Data Carpentry](https://datacarpentry.org/lessons/) lessons are a fantastic resource.

* [**Plotting and Programming in Python**](http://swcarpentry.github.io/python-novice-gapminder/)
* [**Python for Atmosphere and Ocean Scientists**](https://carpentrieslab.github.io/python-aos-lesson/)
* [**Geospatial Data Workshop**](https://datacarpentry.org/geospatial-workshop/)

---

# How can I look at what I have installed in Anaconda?

You can use `conda list` from your terminal shell, which will list all of the packages you've installed.

You can also click on the environment of interest in the Anaconda Navigator; the list will be there.

---

# Can I install R or Julia?

Yes!  You can create a conda environment that lets you run a lot of languages.
* Install Julia by creating a new environment (called `julia`) and then installing the language from the conda-forge channel.  The command below does all this in one line:  
`conda create -n julia -c conda-forge julia`
* See [here](https://docs.anaconda.com/anaconda/user-guide/tasks/use-r-language/) for installing R.

---

# Today (week 2):  Jupyter Notebook, basic coding practice, and adding new libraries to Anaconda

**By the end of today, you'll be able to:**
1. Open a Jupyter Notebook

2. Practice code

3. Install extra libraries in Anaconda
  * `xarray` and `netcdf4`
  * `cartopy`

## Start by cloning the repository to your local machine.

#### If you have bash:
1. Open a terminal shell

2. Navigate to a place you'd like this repository to live:  
```cd ~/Desktop```  
or  
```cd ~/Downloads```  
... etc.

3. Clone the GitHub repository:  
```git clone https://github.com/bairdlangenbrunner/ESS-Python-Tutorial```

#### If you're less familiar with terminals/bash:
1. Navigate to [https://github.com/bairdlangenbrunner/ESS-Python-Tutorial](https://github.com/bairdlangenbrunner/ESS-Python-Tutorial)

2. Click the green button to `Clone or download` (choose Download ZIP)

3. Move that .zip file somewhere accessible on your computer, and double click to unzip it
