# Experiments with green computing data
## Data about climate
When we can select location of a datacenter, it's the first option. Temperatures in Czech region around Prague ([Jupyter notebook](/examples/ERA5-temperature.ipynb))
![](images/t2mCZ012020.png) and in Findland (LUMI in Kajaani). ![](images/t2mFI1D2020.png) The temperatures are displayed on the same scale with external values included in the max and min values, so all days under -5 are counted in the most dark color.

## Carbon intensity of electricity
![](images/CO2I-CZ-2024-heatmap.png)
## Workload CPU intensity
![](images/Adan15-2024-heatmap.png)
# How-to work with FAIR data repositories
## Get selected data from the repository
* Select and download particular file (or files) from given dataset - [HERE - second cell of the notebook](/examples/ERA5-temperature.ipynb) is an example using Zenodo API via requests.
