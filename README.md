# Gaia DR2 ScoCen

This repository contains python notebooks to retrieve ScoCen stars information from *Gaia DR2*. 

__Gaia_AstroQuery.ipynb__: produces a file with different columns for objects in the Gaia DR2 database if they satisfy some selection criteria.

__Data_Selection.ipynb__: includes an extra step to clean *Gaia DR2* data to avoid bad photometry and colors. This also allows to select the pre-main sequence stars from the *CMD* and create a figure in galactic coordinates to visualize the position of these stars.

__Interactive_Path_Selection.ipynb__: includes the main routine to select the polygon path which will be used to select the pre-main sequence stars.

The equatorial coordinates (__Ra__, __Dec__), as well as the galactic coordinates (__l__, __b__) for each pre-main sequence star are saved in a coordinates file. 

# License

The code is released under a MIT license. MIT is a short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.
