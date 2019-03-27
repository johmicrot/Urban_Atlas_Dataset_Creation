## Guide on how to add a population to UA shapefiles, generate data points, and download images


### 1) Download specific city shapefiles from urban atlas 
	https://land.copernicus.eu/local/urban-atlas/urban-atlas-2012?tab=download
	
### 2) Unzip and put each city folder into the directory ~/Cities/{country name}/Shapefiles_Original/{city folder}

### 3) Run file Modify_Country_Shapefiles.py. It will create a new folder ~/Cities/{country name}/Shapefiles_with_pop/
	
### 4) Unzip AllPopulationEstimates.zip and AllPopulationEstimates_part2.zip into the director ~/Cities/AllPopulationEstimates

### 5) Run creating_all_extracted_data.py

### 6) Run static_maps_api_download_all_cities.py



pysatml taken from https://github.com/adrianalbert/pysatml
unmodified urbanatlas taken from https://github.com/adrianalbert/urban-environments/tree/master/dataset-collection
