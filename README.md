# Savidge2023
Code to reproduce figures in Savidge et al., 2023.

Must begin with running step0.ipynb notebook to process seal data into data format (.pkl files) used for subsequent notebooks (i.e., fig1-8.ipynb). Step0.ipynb will save data files as pickle files which then can easily be read in individual figure notebooks.

Note: fig. 6 notebook requires to be run after fig. 5 notebook to read in proper data ('meltwaterXXarray_file'). Otherwise, notebooks do not depend on each other.

figSX.ipynb are for supplemental figures.

All satellite imagery can be visualized (https://worldview.earthdata.nasa.gov/) and downloaded (https://search.earthdata.nasa.gov/).
