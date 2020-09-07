# Python & SQL Alchemy Surf's Up Analaysis

## Purpose



## Results




## Summary



### 2 Additional queries that could add more weather information

1) We could add a groupby for the stations to better understand the summary statistics by station, something similar to the module, such as session.query(Measurement.station, func.count(Measurement.station)).group_by(Measurement.station) + the additional information that is being researched

2) We could also add in the precipitation information for each month to have precipitation summary statistics next to the temperature summary statistics
