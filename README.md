# DuckDB demo
Uses Census data from Statscan [(1)](https://www12.statcan.gc.ca/census-recensement/2021/dp-pd/prof/details/download-telecharger.cfm?Lang=E&SearchText=105%20Mile%20Post%202&DGUIDlist=2021A00055933845&GENDERlist=1,2,3&STATISTIClist=1,4&HEADERlist=0) and [(2)](https://geosuite.statcan.gc.ca/geosuite/en/index#self) as a testbed for trying out the DuckDB Python API.

I suspect that for most data-analyst types, working with SQL is a more natural experience than trying to remember the Pandas DataFrame API.

## Setup
An `environment.yml`` file is provided for use to install required dependencies in a separate environment using conda, eg.

```
> conda create -f environment.yml
> conda activate geoduck 
```