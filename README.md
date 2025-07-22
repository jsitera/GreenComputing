# Experiments with green computing data
## Data about climate
When we can select the location of a datacenter, it's the first option. Temperatures in Czech region around Prague ([Jupyter notebook](/examples/ERA5-temperature.ipynb))
![](images/t2mCZ012020.png) and in Finland (LUMI in Kajaani). ![](images/t2mFI1D2020.png) The temperatures are displayed on the same scale, so the values external to the selected scale are included in the max and min values. It means here that all days under -5 are counted in the darkest color.
Please note that the free cooling (cooling by radiator without heatpump) is possible where the green and yellow colors are.
## Carbon intensity of electricity
Let's see the carbon intensity of electricity in the same graph view, so the green areas are the lowest carbon intensity.
![](images/CO2I-CZ-2024-heatmap.png)
The cleanest electricity is correlated with times when the free cooling doesn't work (in central and southern Europe).
## Workload CPU intensity
![](images/Adan15-2024-heatmap.png)
# How to work with FAIR data repositories
## Get selected data from the repository
* Select and download particular file (or files) from given dataset - [HERE - second cell of the notebook](/examples/ERA5-temperature.ipynb) is an example using Zenodo API via requests.
