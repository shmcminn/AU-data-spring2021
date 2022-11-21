# Air quality

#### By NPR

[Story](https://www.npr.org/2020/09/23/915723316/1-in-7-americans-have-experienced-dangerous-air-quality-due-to-wildfires-this-ye)

* Download daily data for 3 states [LINK](https://www.epa.gov/outdoor-air-quality-data/download-daily-data)
* Combine data
* Add FIPS codes column
* Filter data to timeframe
* Find max day in each county during timeframe
* Find just counties with 1 day [in categories](https://www.epa.gov/outdoor-air-quality-data/air-data-basic-information#:~:text=%22Unhealthy%22%20AQI%20is%20151%20%2D,experience%20more%20serious%20health%20effects.)
	* hazardous
	* very unhealthy
	* unhelathy
* Merge those counties with population data [downloaded from Census](https://data.census.gov/cedsci/)
* Determine number of days with "very unhealthy" air
