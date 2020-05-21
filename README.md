# NYC-Yellow-Taxi

Explore NYC Yellow-Taxi January dataset to know more about type of data, hours and zones included, to planning which type of hours/zone analysis I would like to consider.

Data wrangling with pandas and seaborn, visualizing data.

Discover:
* There are different months, not only January. Is it a typo?
* There are up tu 55k records of trips with 0 distance. What is thist? Typo?
* Most trips were below 84 miles and $20.

Steps:
* Cast datetime objects to type datetime64. 
* Extract month, day and hour.
* Create time_sections to group hours.
* Calculate trip duration from the difference between pickup hour and dropoff hour.
* Binning distance serie to group data and explore distances.
* Plotting differences between pickup zones and dropoff zones.
* Analyze total_amount. 
* Reducing Dataframe to yellow zone.
* Pivot table hour/zone to get higher demanding zones.