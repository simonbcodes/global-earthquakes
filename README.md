# Global Earthquake Visualizations

This repository collects data from the [USGS API](https://earthquake.usgs.gov/fdsnws/event/1/) and analyzes the results with a variety of different techniques.

The Jupyter notebook for this project, which contains the visualizations and explanations of relevant code, can be found [here](https://nbviewer.jupyter.org/github/simonbcodes/global-earthquakes/blob/master/Global%20Earthquakes.ipynb)

## Installation

To install this project on your system, clone the repository. After this, running:

```
pipenv install --dev
````

should install all dependencies required. From here, you can open the Jupyter notebook and experiment by running:

```
pipenv shell
jupyter notebook
```

This should start the virtual environment for the project, and open a Jupyter notebook server for you to mess with as you desire.

## APIs/Dependencies Used (Also found in Pipfile)

- numpy
- pandas
- requests
- bokeh
- jupyter
- mapboxgl
