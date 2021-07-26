# Housing rental Analysis for San Francisco

Using data visualization including aggregation, interactive visualization, geospatial analysis to find property in the San Francisco market that are viable investment opportunities. 

---

## Technologies

This project leverages python 3.7 with the following packages:

    •  PyViz ecosystem (hvPlot library) - for visualization tools to create interactive data visualizations
    •  Plotly Express visualization library and the Mapbox API - for geospatial data, or location-based data

---

## Installation Guide

The following dependencies needed to be installed before running the application.
    
   # PyViz packages
    conda install -c plotly plotly=4.13.
    conda install -c pyviz hvplot
    conda install -c conda-forge nodejs=12

   # JupyterLab Dependencies
    conda install -c conda-forge jupyterlab=2
    jupyter labextension install jupyterlab-plotly@4.13.0 --no-build
    jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.13.0 --no-build
    jupyter labextension install @pyviz/jupyterlab_pyviz --no-build
    jupyter lab build

  # Set up the Mapbox API
    Register for a public Mapbox API access token 

---

## Application Process

Detail process:

![markdown_image](https://github.com/JuneB2021/Module-2-Challenge/blob/main/markdown_image/Process.png)

---

## Usage

To use the Housing rental Analysis Application, simply run the san_francisco_housing.ipynb. 

---

## Contributors

contact: JuBeaver@hotmail.com

---

## License

MIT
