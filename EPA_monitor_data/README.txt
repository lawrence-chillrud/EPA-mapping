################################################################################

EPA monitor data files overview:

- annual_75.csv contains annual data for all those monitors that make at least 75% of their scheduled observations in a given year. 

- annual_season_75.csv contains annual data for all those monitors that make at least 75% of their scheduled observations in a given season, for all four seasons in a given year.

Therefore, annual_season_75.csv is a subset of annual_75.csv. The difference between the two files can be thought of as a difference in thresholding. 

################################################################################

Metadata for annual_75.csv

Dimensions of data: 13854 x 8
Column names: Monitor.ID, Latitude, Longitude, Datum, State.Name, Year, Arithmetic.Mean, Required.Day.Count

Num. of unique monitors: 1606
Num. of unique locations: 1606
Num. of unique dates: NA (annual data)
Years covered: 2000, 2001, 2002, 2003, 2004, 2005, 2006, 2007, 2008, 2009, 2010, 2011, 2012, 2013, 2014, 2015, 2016

-------------------------------

Discarded metadata: 

Parameter Code: {88101}
POC: {1}
Parameter Name: {PM2.5 - Local Conditions}
Sample Duration: {24 HOUR, 24-HR BLK AVG}
Pollutant Standard: {PM25 24-hour 2012}
Units of Measure: {Micrograms/cubic meter (LC)}
Event Type: {No Events, Events Included}
Observation Percent: {75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98, 99, 100}

################################################################################

Metadata for annual_season75.csv

Dimensions of data: 12857 x 8
Column names: Monitor.ID, Latitude, Longitude, Datum, State.Name, Year, Arithmetic.Mean, Required.Day.Count

Num. of unique monitors: 1571
Num. of unique locations: 1571
Num. of unique dates: NA (annual data)
Years covered: 2000, 2001, 2002, 2003, 2004, 2005, 2006, 2007, 2008, 2009, 2010, 2011, 2012, 2013, 2014, 2015, 2016

-------------------------------

Discarded metadata: 

Parameter Code: {88101}
POC: {1}
Parameter Name: {PM2.5 - Local Conditions}
Sample Duration: {24 HOUR, 24-HR BLK AVG}
Pollutant Standard: {PM25 24-hour 2012}
Units of Measure: {Micrograms/cubic meter (LC)}
Event Type: {No Events, Events Included}
Observation Percent: {75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98, 99, 100}