# Python & SQL Alchemy Surf's Up Analaysis

## Purpose

The purpose of the Surfs Up challenge was to create a connection to a SQLite DB and use sqlalchemy to run queries to attain the summary statistics for the months of June and December. I was tasked with writing the query, then converting the results into a list, then finally into a pandas dataframe. The summary statistics were printed out for both months, ensuring they were matched 100% to what the challenge had.

## Results

Three key differences between the June and December temperature comparison:

- The mean/average temperature between the months was about a 3 degree F difference

- The min temperature in December was 8 degrees lower than June but the max was only 2 degrees lower than June's max

- The standard deviation was larger in the December statistics


## Summary

The results were as a person would expect - June had a higher average/mean temperature and a higher max temperature, while December had a lower average/mean temperature with a lower min and max temperature. Surprisingly, the max temperature was only 2 degrees F lower and the mean/average was only 3 degrees lower. This means the climate in the areas observed stays fairly consistent throughout the seasons, which is definitely not the norm in the contiguous United States.

### 2 Additional queries that could add more weather information

1) We could add a groupby for the stations to better understand the summary statistics by station, something similar to the module, such as session.query(Measurement.station, func.count(Measurement.station)).group_by(Measurement.station) + the additional information that is being researched

2) We could also add in the precipitation information for each month to have precipitation summary statistics next to the temperature summary statistics
