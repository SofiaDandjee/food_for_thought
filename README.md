# ADA Project: Food for thought

### Packages to install

```conda create --name ada_project
conda install -n ada_project pandas geopandas matplotlib plotly scikit-learn scipy seaborn pyshp shapely
conda install -n ada_project -c conda-forge descartes
conda install -n ada_project -c plotly plotly-geo
conda install -n ada_project xlrd
pip3 install jupyterlab "ipywidgets>=7.5"
jupyter labextension install jupyterlab-plotly@4.13.0
