![Open in Codespaces](https://classroom.github.com/assets/open-in-codespaces-abfff4d4e15f9e1bd8274d9a39a0befe03a0632bb0f153d0ec72ff541cedbe34.svg)
# Python Spatial Programming with Geopandas
## Assignment

### Background
We have now worked with Python with the `pandas` library to learn about `DataFrame`s and `geopandas` to learn about `GeoDataFrame`s by following some basic tutorials. This next assignment will use the toy `nybb` database that is popular in the open source software world to work with `geopandas` more exploratively. More specifcially, we will be reproducing some output that we previously did in the QGIS Tutorials.

#### GeoPandas
Read this [tutorial](https://geopandas.org/getting_started/introduction.html)
Browse/read the GeoPandas [user guide](https://geopandas.org/docs/user_guide.html).

- Tutorial: https://geopandas.org/getting_started/introduction.html
- User Guide: https://geopandas.org/docs/user_guide.html

#### Geospatial libraries and notes on documentation 
Geospatial Library Reference:
- [Shapely docs](https://shapely.readthedocs.io/en/stable/manual.html)
- [Geopanda docs](http://geopandas.org/)
- [Pandas docs](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide)

Docs can be good or bad. The docs for above range from "ok" to "good". It helps to have a working knowledge of `pandas` but the docs for `pandas` are quite good for learning and as a reference. `geopandas` actually uses the `shapely` model for geometries and while it needs to be installed, there is little direct interaction with this library on our part except for accessing the `shapely` geometries.

### Objective
The objective of this lab is to reproduce one of the QGIS Tutorials you did previously:
- [Performing spatial joins](http://www.qgistutorials.com/en/docs/3/performing_spatial_joins.html)


### Directions
## Create a new branch to work from. 
Create a new branch named `geopandas`.

## Start your codespace on the `geopandas` branch
From the main GitHub page for this assignment, click `Code` -> `Codespaces` -> `Create codespace on assignment`. This will create the codespace and open a new browser window to connect to the codespace.

![create-codespace.png](./media/create-codespace.png)

## Follow the instructions in `assignment.ipynb` inside your codespace
The details for the assignment are embedded in a Jupyter notebook. You can work through the material in the codespace.

## Deliverables
An open Pull Request from a branch named `geopandas` to be merged with `master` containing the following files:
- `spatial_join.py`
- `spatial_join.png`