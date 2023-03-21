# Savidge2023
Code to reproduce figures in Savidge et al., 2023.

Must begin with running step0.ipynb notebook to process seal data into data format (.pkl files) used for subsequent notebooks (i.e., fig1-8.ipynb). Step0.ipynb will save data files as pickle files in working directory which then can easily be read in individual figure notebooks.

Note: fig. 6 notebook requires to be run after fig. 5 notebook to read in proper data ('meltwaterXXarray_file'). Otherwise, notebooks do not depend on each other.

figSX.ipynb are for supplemental figures.

All MODIS imagery can be visualized in [NASA Worldview](https://worldview.earthdata.nasa.gov/) and downloaded from [NASA Earthdata](https://search.earthdata.nasa.gov/). 2019 Landsat scenes in fig3.ipynb can be downloaded from [USGS EarthExplorer](https://earthexplorer.usgs.gov/).

Seal data can be downloaded here (**insert link once published**).
