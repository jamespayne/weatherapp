# weatherapp
Simple python based web server and client which calls the DarkSky Weather API. This was a university project.

Update as of 07/05/20 DarkSky is discontinuing their API access. See [here](https://blog.darksky.net/).

I'm sure you could use this with some other weather api though. It would just be a matter of changing the API requests when sourcing weather data.

## Aim

* Further improve my python programming skills.
* Introduction to using web APIs.
* Ensure proper exception handling is used.

## Language/Technology Used

* Python
* Darksky Weather Forecasting API

## Dependencies

The only non core module used in this app is dateutil which can be installed using pip:
  
  pip install python-dateutil

I may remove this dependency and update the code to achive the same functionality with a core module in the future.

## Data Sources

**Local**

PTV Timetable and Geographic Information - GTFS

The data source for station locations is from Public Transport Victoria and only uses one file which is located at /google_transit/stops.txt. This data has been included for demonstration purposes only. For the most current data, please visit the PTV Timetable and Geographic Information - GTFS datasource page which can be found [here](https://www.data.vic.gov.au/data/dataset/ptv-timetable-and-geographic-information-2015-gtfs)

## Notes

~~You will need an api key from Darksky to run this application. The key should be stored in a file called forecastKey (no extension) in the root directory. This file has not been included for security reasons.~~

This is old, outdated and a possible security risk. The main script stage2.py references a file called forecastKey. You can use the script this way but it would be better to use an environment variable to store your API key.
