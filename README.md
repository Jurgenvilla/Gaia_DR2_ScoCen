# Gaia_DR2_ScoCen
This repository contains python notebooks to retrieve ScoCen stars information from Gaia DR2. 

Gaia_AstroQuery.ipynb produces a file with different columns for objects in the Gaia DR2 database if they satisfy some selection criteria.

Data_Selection.ipynb includes an extra step to clean Gaia DR2 data to avoid bad photometry and colors. This also allows to select the pre-main sequence stars from the CMD and create a figure in galactic coordinates to visualize the position of these stars.

The Ra and Dec, as well as the galactic coordinates (l, b) for each pre-main sequence star are saved in a coordinates file. 
