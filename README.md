# OSMnx Examples: London Boroughs

![London_Street_Orientations](https://raw.githubusercontent.com/jaredbest/osmnx-examples-london-boroughs/master/images/london_street_orientations.png)

You can run these OSMnx example notebooks locally with the official OSMnx [docker image](https://hub.docker.com/r/gboeing/osmnx).

All of the examples are in this repo's [notebooks](notebooks) folder.

OSMnx is a Python package to work with street networks: retrieve, model, analyze, and visualize street networks and other spatial data from OpenStreetMap.

## Using OSMnx in a Docker Container

1. Download and install [Docker](https://www.docker.com/).
2. Open Command Prompt and change directories to a folder containing a Jupyter notebook that you would like to run.
3. On Windows OS, run the following command:
   ```
   docker run --rm -it --name osmnx -p 8888:8888 -v "%cd%":/home/jovyan/work gboeing/osmnx
   ```
4. Visit http://localhost:8888 in your browser to launch JupyterLab.

### More Information

- [Overview of OSMnx](https://geoffboeing.com/2016/11/osmnx-python-street-networks/)
- [GitHub repo](https://github.com/gboeing/osmnx)
- [Examples, demos, tutorials](https://github.com/gboeing/osmnx-examples)
- [Documentation](https://osmnx.readthedocs.io/)
- [Journal article and citation info](https://geoffboeing.com/publications/osmnx-complex-street-networks/)
