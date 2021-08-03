# Oregon_fire_data

Data was extraced from the Oregon department of forestry database site at https://apps.odf.oregon.gov/DIVISIONS/protection/fire_protection/fires/FIRESlist.asp
data includes 1960 through June 2021 fire data.  Multiple pulls were required to extract the data due to limits on single pulls. Total file is in csv format and includes 64,371 rows.
geospatial data was converted from degrees to decimel format for Tableau compatibility.  Fuel Model was mapped to key and the extended fuel model was added as a field:

## Dictionary
 - RecordID - integer - Unique key to records
 - fire_year - integer - year fire was recorded 
 - district - string - ODF district that handled the fire
 - unit - string - ODF Unit handling the fire
 - fire_number - integer - ODF fire identifier
 - fire_name - string - name of fire
 - legal - string - presumably legal identifier for fire
 - latitude_degrees - string - latitude of fire in degrees
 - longitude_degrees - string - longitude of fire in degrees
 - latitude_decimal - decimal equvalent of latitude
 - longitude_decimal - decimal equivalent of Longitude
 - fuel_model - string - coded information on teh fire fuel
 - fuel_model_extended - string - decoded discription of fuel model
 - county - string - Oregon county associated with the fire
 - report_date - date fire report was logged
 - general cause - attributed cause of fire
 - odf_acres - size of the fire in acres in terms of acerage odf adminsters
 - total_acres - size of fire  generaly odf_acres and total_acres seem to report the same number
 
