# DataCleaning_HoustonCrime
Here I am trying to show the process of data cleaning using python. I got my data set from the City of Houston Crime Reports (https://www.houstontx.gov/police/cs/Monthly_Crime_Data_by_Street_and_Police_Beat.htm)
You can visit the city of houston website to get more specific infomration regarding the crime reports. I have attached the specific files to this repo so you can download them if you prefer to not
go to the Houston website and just want to work with the data set.

Once we are done cleaning the data a bit you might want to graph some of the data on a map. There are a  few ways to do this. One is you can get a google API, and plot them on google maps.
I am not going to utilize that method, because the free version has a limit. I am going to utilize geopandas, and to graph our coordinates we are going to need a shape file(.shp) for the county.
you can find the Harris County .shp file here: https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2024&layergroup=All+Lines. If you are doing something similar for your county, you can just look look up your state and county on this same page, and you will have the option to download the .shp file.
