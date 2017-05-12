# IBM_DSX_demo
This is a repo for giving tutorial on IBM DSX

If you want to get building footprints working on IBM DSX
git clone the following project:
https://Henrilin28@gitlab.com/Henrilin28/citydata.git

import geopandas as gpd


file too big may not work
df = gpd.read('./citydata/bluiding_footprints.geojson')

df.plot()
