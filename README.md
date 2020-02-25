# InstallationNotesToSelf

## GDAL
Recommend a clean environment because geoml uses GDAL through rasterio and geopandas. It is known to cause problems if you try to install it in a packed environement. You can do:

> conda create -n envname python=3.7

> conda activate envname

> conda install rasterio geopandas

Extra comment: If you use windows you should set the path of GDAL by yourself.
