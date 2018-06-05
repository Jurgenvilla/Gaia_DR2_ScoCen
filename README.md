# Gaia DR2 ScoCen

This repository contains python notebooks to reproduce the Color-Magnitude diagram of Sco-Cen region drawn by the young stellar population using *Gaia DR2* data. 

![scocen_coordinates](https://user-images.githubusercontent.com/2405448/40990909-8bfaac96-68f2-11e8-85fc-c656e30c0a59.png)

__Gaia_AstroQuery.ipynb__: produces a file with different columns for objects in the Gaia DR2 database, if they satisfy some selection criteria.

__Data_Selection.ipynb__: includes an extra step to clean *Gaia DR2* data to avoid bad photometry and colors. This file also allows to select the pre-main sequence stars from the *CMD* and create a figure in galactic coordinates to visualize the position of these stars.

__Interactive_Path_Selection.ipynb__: includes the main routine to select the polygon path which will be used to select the pre-main sequence stars.

The equatorial coordinates (__Ra__, __Dec__), as well as the galactic coordinates (__l__, __b__) for each pre-main sequence star,  are saved in a coordinates file. 

# Requirements

__Astropy__ (http://www.astropy.org/), __Astroquery__ (http://astroquery.readthedocs.io/en/latest/) and __Matplotlib__ (https://matplotlib.org/) are needed to execute the notebooks properly. 

The notebooks need to be executed in this order: 

__(i)__  Gaia_AstroQuery.ipynb to obtain the data.

__(ii)__ Interactive_Path_Selection.ipynb if the user wants to select their own region. 

__(iii)__ Data_Selection.ipynb can be used directly after step __(i)__ to use the original path selected in our sample. 

An original copy is saved in folder __Original_Copy__; thus, the user can run the notebooks, modify the queries and paths, overwriting the files and compare to the original selection in our work. 

# License

The code is released under an MIT license. MIT is a short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications and larger works may be distributed under different terms and without source code.
