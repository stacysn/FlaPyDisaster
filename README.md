# FlaPyDisaster
Hurricane modelling and mapping program written in Python and Flask, with Leaflet for mapping, implementing the NOAA NWS 23 parametric hurricane model. 

## Installation

### Environments
Anaconda is recommended for setting up the python environment for this program.  Install from the appropriate requirements file using `conda install --file conda_requirements_XXXX.txt`.  Explicit has web URLs for the conda packages.

Pip can also work, but its not supported right now because GDAL has dependency probelms with pip.  GDAL has to be installed on the host machine, and the gdal package will have to be replaced with pygdal.  Note that these restrictions on GDAL might not matter when not using a virtual evnironment.

## Development
#### IMPORTANT: To run in IDEs in windows with anaconda, the anaconda environment directory (ex: ...\Anaconda2\envs\EnvironmentName) must be included in PATH
It can either be included globably or as a setting in the IDE, doesn't really matter.  Alternatively, activate the anaconda environment and run app.py, that will handle setting the PATH.

I've used both IntellJ Idea and Visual Studio 2015 Community Edition with success, there shouldn't be anything preventing other IDEs though.

## Documentation
Documentation is linked here because its included in the program
[Documentation link](https://github.com/cliftbar/FlaPyDisaster/blob/master/FlaPyDisaster/static/markdown/documentation_main.md)
